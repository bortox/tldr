---
author: ['Dmitry Nikolayev', 'Emily Grace Seville', 'Jonathan Dahan']
date: 1644837703
title: "split"
description: "split, Split a file into pieces."
categories: "osx"
---
> More information: <https://ss64.com/osx/split.html>.

- Split a file, each split having 10 lines (except the last split):

```bash
split -l 10 filename
```

- Split a file by a regular expression. The matching line will be the first line of the next output file:

```bash
split -p cat|^[dh]og filename
```

- Split a file with 512 bytes in each split (except the last split; use 512k for kilobytes and 512m for megabytes):

```bash
split -b 512 filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Jonathan Dahan](mailto:hi@jonathan.is) | fix dog/hog/dhog split | 2019-01-15T23:55:41 | [f09b0dc4c881](https://github.com/tldr-pages/tldr/commit/f09b0dc4c88158a652ddb82d2f086de733c5f1ef)
[Jonathan Dahan](mailto:hi@jonathan.is) | add example of splitting by animal name | 2019-01-15T23:55:41 | [e8a6135117e2](https://github.com/tldr-pages/tldr/commit/e8a6135117e2bb1819a6492e4996247bab927c33)
[Jonathan Dahan](mailto:hi@jonathan.is) | split: mention regex instead of pattern | 2019-01-15T23:55:41 | [3768c57acbb2](https://github.com/tldr-pages/tldr/commit/3768c57acbb2d2c727acd5436d90218eb31434fe)
[Jonathan Dahan](mailto:hi@jonathan.is) | split: remove split into n files, add split by pattern | 2019-01-15T23:55:41 | [bcda9b60e3ef](https://github.com/tldr-pages/tldr/commit/bcda9b60e3ef2ea9a1590bfd1b50c2cc4a08d418)
[Dmitry Nikolayev](mailto:dsnikolaev@gmail.com) | split: add `-b` option; clarify the behaviour of `-C` option (#2083) | 2018-04-30T09:55:28 | [2dd55cabbaf8](https://github.com/tldr-pages/tldr/commit/2dd55cabbaf86867fd0c67ed16f5fd532fefc4fc)

