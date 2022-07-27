---
author: ['Alex Larsen', 'pxgamer', 'pixel', 'Guido Lena Cota', 'bl-ue']
date: 1631455407
title: "scheme, TLDR Pages"
description: "scheme, MIT Scheme language interpreter and REPL (interactive shell)."
categories: "common"
---
> More information: <https://www.gnu.org/software/mit-scheme>.

- Start a REPL (interactive shell):

```bash
scheme
```

- Run a scheme program (with no REPL output):

```bash
scheme --quiet < script.scm
```

- Load a scheme program into the REPL:

```bash
scheme --load script.scm
```

- Load scheme expressions into the REPL:

```bash
scheme --eval "(define foo 'x)"
```

- Open the REPL in quiet mode:

```bash
scheme --quiet
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | pages/common/*.md: REPL Normalization (#6471) | 2021-09-12T16:03:27 | [882781e41019](https://github.com/tldr-pages/tldr/commit/882781e41019543fd716442e62faa1fb02d474b9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | scheme: add link to homepage | 2019-05-29T14:41:10 | [ef54bda5ba85](https://github.com/tldr-pages/tldr/commit/ef54bda5ba85d073f47807373e3f906e4dbd0fe9)
[Alex Larsen](mailto:alex0112@users.noreply.github.com) | scheme: add page (#2511) | 2018-10-30T16:04:59 | [f323e9fc9a52](https://github.com/tldr-pages/tldr/commit/f323e9fc9a529104cdc38dcc95f5139658fa66ea)

