---
author: ['Benedek Szilvasy']
date: 1634056367
title: "raco, TLDR Pages"
description: "raco, Racket command-line tools."
categories: "common"
---
> More information: <https://docs.racket-lang.org/raco/>.

- Install a package, automatically installing dependencies:

```bash
raco pkg install --auto package_source
```

- Install the current directory as a package:

```bash
raco pkg install
```

- Build (or rebuild) bytecode, documentation, executables, and metadata indexes for collections:

```bash
raco setup collection1 collection2 ...
```

- Run tests in files:

```bash
raco test path/to/tests1.rkt path/to/tests2.rkt ...
```

- Search local documentation:

```bash
raco docs search_terms ...
```

- Display help:

```bash
raco help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Benedek Szilvasy](mailto:benedek.szilvasy@gmail.com) | raco: add page (#6955) | 2021-10-12T18:32:47 | [aaed3c64aff6](https://github.com/tldr-pages/tldr/commit/aaed3c64aff651546cefbeb45a8025f7847656b1)

