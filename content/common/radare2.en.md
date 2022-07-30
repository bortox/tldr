---
author: ['Patrick Kuehn']
date: 1571790035
title: "radare2"
description: "radare2, A set of reverse engineering tools."
categories: "common"
---
> More information: <https://radare.gitbooks.io/radare2book/>.

- Open a file in write mode without parsing the file format headers:

```bash
radare2 -nw path/to/binary
```

- Debug a program:

```bash
radare2 -d path/to/binary
```

- Run a script before entering the interactive CLI:

```bash
radare2 -i path/to/script.r2 path/to/binary
```

- Show help text for any command in the interactive CLI:

```bash
> radare2_command?
```

- Run a shell command from the interactive CLI:

```bash
> !shell_command
```

- Dump raw bytes of current block to a file:

```bash
> pr > path/to/file.bin
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrick Kuehn](mailto:pkpatrickkuehn@googlemail.com) | radare2: add page (#3433) | 2019-10-23T02:20:35 | [ec7a7bb251e4](https://github.com/tldr-pages/tldr/commit/ec7a7bb251e47bf77ba313941252ddfb6d356e93)

