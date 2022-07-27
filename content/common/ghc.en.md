---
author: ['pixel', 'Daniel Campoverde [alx741]', 'mira01', 'pxgamer']
date: 1631455407
title: "ghc, TLDR Pages"
description: "ghc, The Glasgow Haskell Compiler."
categories: "common"
---
> Compiles and links Haskell source files.

> More information: <https://www.haskell.org/ghc>.

- Find and compile all modules in the current directory:

```bash
ghc Main
```

- Compile a single file:

```bash
ghc file.hs
```

- Compile using extra optimization:

```bash
ghc -O file.hs
```

- Stop compilation after generating object files (.o):

```bash
ghc -c file.hs
```

- Start a REPL (interactive shell):

```bash
ghci
```

- Evaluate a single expression:

```bash
ghc -e expression
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | pages/common/*.md: REPL Normalization (#6471) | 2021-09-12T16:03:27 | [882781e41019](https://github.com/tldr-pages/tldr/commit/882781e41019543fd716442e62faa1fb02d474b9)
[pxgamer](mailto:owzie123@gmail.com) | ghc: add link to homepage | 2019-06-07T23:58:59 | [ddb88bb42253](https://github.com/tldr-pages/tldr/commit/ddb88bb422535c86259890e17127daf97bf49a96)
[mira01](mailto:miracech@email.cz) | ghc: add evaluate expression example (#2439) | 2018-10-13T18:51:33 | [686f17dd7262](https://github.com/tldr-pages/tldr/commit/686f17dd72621d43866a551fd2f85430f1901dd6)
[Daniel Campoverde [alx741]](mailto:alx741@riseup.net) | ghc: more explicit | 2016-05-05T18:33:43 | [164f1c999731](https://github.com/tldr-pages/tldr/commit/164f1c999731cb4f81737542d5fdea3496c72cc6)
[Daniel Campoverde [alx741]](mailto:alx741@riseup.net) | ghc: add page | 2016-05-05T03:22:26 | [8e84a6871131](https://github.com/tldr-pages/tldr/commit/8e84a687113103ca8067f06fd8840f8015def118)

