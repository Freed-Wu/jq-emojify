# jq-emojify

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/Freed-Wu/jq-emojify/main.svg)](https://results.pre-commit.ci/latest/github/Freed-Wu/jq-emojify/main)

[![github/downloads](https://shields.io/github/downloads/Freed-Wu/jq-emojify/total)](https://github.com/Freed-Wu/jq-emojify/releases)
[![github/downloads/latest](https://shields.io/github/downloads/Freed-Wu/jq-emojify/latest/total)](https://github.com/Freed-Wu/jq-emojify/releases/latest)
[![github/issues](https://shields.io/github/issues/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/issues)
[![github/issues-closed](https://shields.io/github/issues-closed/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/issues?q=is%3Aissue+is%3Aclosed)
[![github/issues-pr](https://shields.io/github/issues-pr/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/pulls)
[![github/issues-pr-closed](https://shields.io/github/issues-pr-closed/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/pulls?q=is%3Apr+is%3Aclosed)
[![github/discussions](https://shields.io/github/discussions/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/discussions)
[![github/milestones](https://shields.io/github/milestones/all/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/milestones)
[![github/forks](https://shields.io/github/forks/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/network/members)
[![github/stars](https://shields.io/github/stars/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/stargazers)
[![github/watchers](https://shields.io/github/watchers/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/watchers)
[![github/contributors](https://shields.io/github/contributors/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/graphs/contributors)
[![github/commit-activity](https://shields.io/github/commit-activity/w/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/graphs/commit-activity)
[![github/last-commit](https://shields.io/github/last-commit/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/commits)
[![github/release-date](https://shields.io/github/release-date/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/releases/latest)

[![github/license](https://shields.io/github/license/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify/blob/main/LICENSE)
[![github/languages](https://shields.io/github/languages/count/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify)
[![github/languages/top](https://shields.io/github/languages/top/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify)
[![github/directory-file-count](https://shields.io/github/directory-file-count/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify)
[![github/code-size](https://shields.io/github/languages/code-size/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify)
[![github/repo-size](https://shields.io/github/repo-size/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify)
[![github/v](https://shields.io/github/v/release/Freed-Wu/jq-emojify)](https://github.com/Freed-Wu/jq-emojify)

A jq script to convert emoji name such as `:smile:` to emoji character
such as :smile:.

Emoji map is not hard encoded to main script, which is the biggest difference
from other similar projects, in order to update emoji map easier.

## Related Projects

- [github/gemoji](https://github.com/github/gemoji): the earliest project.
  Written in ruby. Contain a json file which is the standard about the map
  between emoji names and emoji characters. Always latest. Provide a ruby port.
  Used in github and jekyll.
- [mrowa44/emojify](https://github.com/mrowa44/emojify): the most famous project.
  Written in bash. Supported by many package managers. Provide a CLI port.
- [twuni/emojify](https://github.com/twuni/emojify): written in javascript.
  Provide a js port.
- [filipekiss/zemojify](https://github.com/filipekiss/zemojify): written in zsh.
  Provide a CLI port.
- [lord63/pyemojify](https://github.com/lord63/pyemojify): written in python.
  Provide a python port and a CLI port.

Except [github/gemoji](https://github.com/github/gemoji), the other projects is
not latest.
Because [github/gemoji](https://github.com/github/gemoji) uses json to store the
map between emoji names and emoji characters. I think jq is a good choice.

## Install

### AUR

```sh
paru -S jq-emojify
```

### NUR

```sh
nix-env -iA nur.repos.Freed-Wu.jq-emojify
```

### PPA

```sh
add-apt-repository ppa:freedwu/ppa
apt update
apt install jq-emojify
```
