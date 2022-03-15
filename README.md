# gh-parallel

## Table of Contents


### gh-parallel
- [gh-parallel](#gh-parallel)
  - [Table of Contents](#table-of-contents)
    - [gh-parallel](#gh-parallel-1)
    - [Badges](#badges)
  - [Summary](#summary)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Code of Conduct](#code-of-conduct)
  - [Changes](#changes)
  - [Author](#author)

### Badges

[![License](https://img.shields.io/badge/License-Apache%202.0-yellowgreen.svg)](https://opensource.org/licenses/Apache-2.0)
[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/p6m7g8/gh-parallel)
[![Mergify](https://img.shields.io/endpoint.svg?url=https://gh.mergify.io/badges/p6m7g8/gh-parallel/&style=flat)](https://mergify.io)
[![codecov](https://codecov.io/gh/p6m7g8/gh-parallel/branch/master/graph/badge.svg?token=14Yj1fZbew)](https://codecov.io/gh/p6m7g8/gh-parallel)
[![Known Vulnerabilities](https://snyk.io/test/github/p6m7g8/gh-parallel/badge.svg?targetFile=package.json)](https://snyk.io/test/github/p6m7g8/gh-parallel?targetFile=package.json)
[![Gihub repo dependents](https://badgen.net/github/dependents-repo/p6m7g8/gh-parallel)](https://github.com/p6m7g8/gh-parallel/network/dependents?dependent_type=REPOSITORY)
[![Gihub package dependents](https://badgen.net/github/dependents-pkg/p6m7g8/gh-parallel)](https://github.com/p6m7g8/gh-parallel/network/dependents?dependent_type=PACKAGE)

## Summary

After:
![after](assets/after.jpg)

Before:
![before](assets/before.jpg)

This requires `gnu parallel` to be installed. Which it will then make use of to parallelize clone and sync requests.

This is quite useful to clone organizations faster and or a list of disparate repositories.

## Usage

```shell
Usage:
  gh parallel -h
  gh parallel list [<login> [-- <list options>] | -h]
  gh parallel clone [<login> <dest_dir> [-- <clone options] | -h]
```

## Contributing

- [How to Contribute](CONTRIBUTING.md)

## Code of Conduct

- [Code of Conduct](https://github.com/p6m7g8/.github/blob/master/CODE_OF_CONDUCT.md)

## Changes

- [Change Log](CHANGELOG.md)

## Author

Philip M . Gollucci <pgollucci@p6m7g8.com>
