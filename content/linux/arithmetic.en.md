---
author: ['Sahil Dhiman']
date: 1603545172
title: "arithmetic"
description: "arithmetic, Quiz on simple arithmetic problems."
categories: "linux"
---
> More information: <https://manpages.debian.org/bsdgames/arithmetic.6.en.html>.

- Start an arithmetic quiz:

```bash
arithmetic
```

- Specify one or more arithmetic [o]peration symbols to get problems on them:

```bash
arithmetic -o +|-|x|/
```

- Specify a range. Addition and multiplication problems would feature numbers between 0 and range, inclusive. Subtraction and division problems would have required result and number to be operated on, between 0 and range:

```bash
arithmetic -r 7
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | arithmetic: add page (#4786) | 2020-10-24T15:12:52 | [2a1b2fbd3d71](https://github.com/tldr-pages/tldr/commit/2a1b2fbd3d71bc256dc941615b9e107f2d424246)

