---
author: ['Eddie Antonio Santos', 'Ruben Vereecken', 'Gil Moskowitz']
date: 1633789126
title: "strings, TLDR Pages"
description: "strings, Find printable strings in an object file or binary."
categories: "common"
---
> More information: <https://manned.org/strings>.

- Print all strings in a binary:

```bash
strings file
```

- Limit results to strings at least *length* characters long:

```bash
strings -n length file
```

- Prefix each result with its offset within the file:

```bash
strings -t d file
```

- Prefix each result with its offset within the file in hexadecimal:

```bash
strings -t x file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gil Moskowitz](mailto:gmoskowitz@xtuple.com) | strings: add more information link (#6914) | 2021-10-09T16:18:46 | [5e1fe48e39f5](https://github.com/tldr-pages/tldr/commit/5e1fe48e39f5733e980ad41a3a5cc25dc534ea53)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Eddie Antonio Santos](mailto:easantos@ualberta.ca) | strings: add page | 2015-12-30T23:22:13 | [85cde43d8534](https://github.com/tldr-pages/tldr/commit/85cde43d8534fb4e1bbb2fa9069e8ff5579261f1)

