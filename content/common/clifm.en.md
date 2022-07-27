---
author: ['leo-arch']
date: 1642509592
title: "clifm, TLDR Pages"
description: "clifm, The command line file manager."
categories: "common"
---
> More information: <https://github.com/leo-arch/clifm>.

- Start CliFM:

```bash
clifm
```

- Open the file or directory whose ELN (entry list number) is 12:

```bash
12
```

- Create a new file and a new directory:

```bash
n file dir/
```

- Search for PDF files in the current directory:

```bash
/*.pdf
```

- Select all PNG files in the current directory:

```bash
s *.png
```

- Remove the previously selected files (use `t` to send the files to the recycle bin instead):

```bash
r sel
```

- Display detailed help:

```bash
?
```

- Exit CliFM:

```bash
q
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[leo-arch](mailto:leonardoabramovich2@gmail.com) | clifm: add page (#7645) | 2022-01-18T13:39:52 | [0e9bf6b39650](https://github.com/tldr-pages/tldr/commit/0e9bf6b396502db16df0241698409022f67cfbf5)

