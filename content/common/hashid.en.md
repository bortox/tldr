---
author: ['João C Fukuda']
date: 1634182022
title: "hashid"
description: "hashid, Python3 program that identifies data and password hashes."
categories: "common"
---
> More information: <https://github.com/psypanda/hashID>.

- Identify hashes from standard input (through typing, copying and pasting, or piping the hash into the program):

```bash
hashid
```

- Identify hashes passed as arguments (multiple hashes can be passed):

```bash
hashid hash
```

- Identify hashes on a file (one hash per line):

```bash
hashid path/to/hashes.txt
```

- Show all possible hash types (including salted hashes):

```bash
hashid --extended hash
```

- Show `hashcat`'s mode number and `john`'s format string of the hash types:

```bash
hashid --mode --john hash
```

- Save output to a file instead of printing to standard output:

```bash
hashid --outfile path/to/output.txt hash
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[João C Fukuda](mailto:37672942+JoaoFukuda@users.noreply.github.com) | hashid: add page (#6829) | 2021-10-14T05:27:02 | [453ca6d4b4ad](https://github.com/tldr-pages/tldr/commit/453ca6d4b4ad2d2e54f7b3871d01c9153b7df9b3)

