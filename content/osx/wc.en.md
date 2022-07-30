---
author: ['Krzysztof Bociurko', 'Emily Grace Seville', 'Abel']
date: 1644837703
title: "wc"
description: "wc, Count lines, words, or bytes."
categories: "osx"
---
> More information: <https://ss64.com/osx/wc.html>.

- Count lines in file:

```bash
wc -l path/to/file
```

- Count words in file:

```bash
wc -w path/to/file
```

- Count characters (bytes) in file:

```bash
wc -c path/to/file
```

- Count characters in file (taking multi-byte character sets into account):

```bash
wc -m path/to/file
```

- Use standard input to count lines, words and characters (bytes) in that order:

```bash
find . | wc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | w, wc: add Polish translation (#7327) | 2021-11-04T11:06:14 | [8fa4693fbac0](https://github.com/tldr-pages/tldr/commit/8fa4693fbac038dc16c8ed23f5006912abea7ee3)
[Abel](mailto:abel.tay@gmail.com) | wc: split osx and common platform (#6834) | 2021-10-13T19:32:18 | [ba2a835251f1](https://github.com/tldr-pages/tldr/commit/ba2a835251f1027b7e8f81ac7fabbc9648a75fbc)

