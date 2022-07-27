---
author: ['Ethan Kinnear']
date: 1658330838
title: "licensor, TLDR Pages"
description: "licensor, Write licenses to stdout."
categories: "common"
---
> More information: <https://github.com/raftario/licensor>.

- Write the MIT license to a file named `LICENSE`:

```bash
licensor MIT > LICENSE
```

- Write the MIT license with a [p]laceholder copyright notice to a file named `LICENSE`:

```bash
licensor -p MIT > LICENSE
```

- Specify a copyright holder named Bobby Tables:

```bash
licensor MIT "Bobby Tables" > LICENSE
```

- Specify licence exceptions with a WITH expression:

```bash
licensor "Apache-2.0 WITH LLVM-exception" > LICENSE
```

- List all available licenses:

```bash
licensor --licenses
```

- List all available exceptions:

```bash
licensor --exceptions
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ethan Kinnear](mailto:contact@superatomic.dev) | licensor: add page (#8204) * licensor: add page * licensor: use mnemonic for "placeholder" Co-authored-by: Emily Grace Seville [...] | 2022-07-20T17:27:18 | [efd2a87d9270](https://github.com/tldr-pages/tldr/commit/efd2a87d9270b1970678bb09e5c5cd411f6565fe)

