---
author: ['pixel']
date: 1630843905
title: "carp, TLDR Pages"
description: "carp, REPL and build tool for Carp."
categories: "common"
---
> More information: <https://carp-lang.github.io/carp-docs/Manual.html>.

- Start a REPL (interactive shell):

```bash
carp
```

- Start a REPL with a custom prompt:

```bash
carp --prompt "> "
```

- Build a `carp` file:

```bash
carp -b path/to/file.carp
```

- Build and run a file:

```bash
carp -x path/to/file.carp
```

- Build a file with optimizations enabled:

```bash
carp -b --optimize path/to/file.carp
```

- Transpile a file to C code:

```bash
carp --generate-only path/to/file.carp
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | carp: add page (#6456) | 2021-09-05T14:11:45 | [eb3975485dc3](https://github.com/tldr-pages/tldr/commit/eb3975485dc3913880bbbd072d391f1a90cb2db7)

