---
author: ['Juri']
date: 1602286039
title: "ghci, TLDR Pages"
description: "ghci, The Glasgow Haskell Compiler's interactive environment."
categories: "common"
---
> More information: <https://downloads.haskell.org/ghc/latest/docs/html/users_guide/ghci.html>.

- Start a REPL (interactive shell):

```bash
ghci
```

- Start a REPL and load the specified Haskell source file:

```bash
ghci source_file.hs
```

- Start a REPL and enable a language option:

```bash
ghci -Xlanguage_option
```

- Start a REPL and enable some level of compiler warnings (e.g. `all` or `compact`):

```bash
ghci -Wwarning_level
```

- Start a REPL with a colon-separated list of directories for finding source files:

```bash
ghci -ipath/to/directory1:path/to/directory2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | ghci: add page (#4576) | 2020-10-10T01:27:19 | [8994f18ea458](https://github.com/tldr-pages/tldr/commit/8994f18ea4580e776d91bcdf8c60619b7968616a)

