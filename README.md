# `nfg`
> Install Node modules from GitHub using `npm` under the hood.

[![Build Status](https://travis-ci.org/kevingimbel/nfg.svg?branch=master)](https://travis-ci.org/kevingimbel/nfg)

`nfg` (_node from git_) is a wrapper around the npm package manager to install node packages from GitHub.com

## Install

Install with `npm` by executing the following command inside a terminal:

```sh
$ npm i -g nfg
```

## Usage

Afterwards installation is completed can use `nfg` to install node modules from GitHub.com by specifiying the source as `username/repo`, for example

```sh
$ nfg -g kevingimbel/leetscript-cli
$ nfg lynzt/fs_readfile
```

The last argument is always the repository. All options like `-g` are passed to `npm` directly.

## Why?

I'm a lazy person and I don't like to type `npm install ssh+git://git@github.com/user/repo` when installing from private repositories. 😬
