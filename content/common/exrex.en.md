---
author: ['Seth Falco', 'bl-ue']
date: 1629050349
title: "exrex, TLDR Pages"
description: "exrex, Generate all/random matching strings for a regular expression."
categories: "common"
---
> It can also simplify regular expressions.

> More information: <https://github.com/asciimoo/exrex>.

- Generate all possible strings that match a regular expression:

```bash
exrex 'regular_expression'
```

- Generate a random string that matches a regular expression:

```bash
exrex --random 'regular_expression'
```

- Generate at most 100 strings that match a regular expression:

```bash
exrex --max-number 100 'regular_expression'
```

- Generate all possible strings that match a regular expression, joined by a custom delimiter string:

```bash
exrex --delimiter ", " 'regular_expression'
```

- Print count of all possible strings that match a regular expression:

```bash
exrex --count 'regular_expression'
```

- Simplify a regular expression:

```bash
exrex --simplify 'ab|ac'
```

- Print eyes:

```bash
exrex '[oO0](_)[oO0]'
```

- Print a boat:

```bash
exrex '( {20}(\| *\\|-{22}|\|)|\.={50}| ( ){0,5}\\\.| {12}~{39})'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | exrex: add page (#5296) | 2021-02-25T18:46:24 | [473b1ac11a68](https://github.com/tldr-pages/tldr/commit/473b1ac11a68233184fb6cd9ecb0bae0cdf1b0b1)

