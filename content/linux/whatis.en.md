---
author: ['Starbeamrainbowlabs', 'Emily Grace Seville']
date: 1647882468
title: "whatis, TLDR Pages"
description: "whatis, Display one-line descriptions from manual pages."
categories: "linux"
---
> More information: <https://manned.org/whatis>.

- Display a description from a man page:

```bash
whatis command
```

- Don't cut the description off at the end of the line:

```bash
whatis --long command
```

- Display descriptions for all commands matching a glob:

```bash
whatis --wildcard net*
```

- Search man page descriptions with a regular expression:

```bash
whatis --regex 'wish[0-9]\.[0-9]'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | whatis: add glob example (#1365) | 2017-05-04T09:38:06 | [e8d141b6c47b](https://github.com/tldr-pages/tldr/commit/e8d141b6c47b279deac402348669d9ece9c6f149)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | whatis: add page (#1078) | 2016-09-19T19:36:07 | [7356a47e02ae](https://github.com/tldr-pages/tldr/commit/7356a47e02ae2da94da9736963a51ef7cc34c23c)

