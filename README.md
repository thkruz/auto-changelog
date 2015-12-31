auto-changelog
==============

Command line tool for generating a changelog from git tags and commit history

[![Latest npm version](https://img.shields.io/npm/v/auto-changelog.svg)](https://www.npmjs.com/package/auto-changelog)
[![Build Status](https://img.shields.io/travis/CookPete/auto-changelog.svg)](https://travis-ci.org/CookPete/auto-changelog)
[![Dependency Status](https://img.shields.io/david/CookPete/auto-changelog.svg)](https://david-dm.org/CookPete/auto-changelog)
[![devDependency Status](https://img.shields.io/david/dev/CookPete/auto-changelog.svg)](https://david-dm.org/CookPete/auto-changelog#info=devDependencies)

### Installation

```bash
npm install -g auto-changelog
```

### Usage

Just run in a local git repo. `git log` is run behind the scenes in order to parse commits.

```bash
auto-changelog # Writes log to CHANGELOG.md in current directory
```

Specify an output file with `-o` or `--output`

```bash
auto-changelog --output HISTORY.md # Writes log to HISTORY.md
```