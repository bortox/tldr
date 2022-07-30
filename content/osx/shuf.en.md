---
author: ['SAURABH SHARMA', 'Emily Grace Seville']
date: 1644837703
title: "shuf"
description: "shuf, Generate random permutations."
categories: "osx"
---
> More information: <https://www.unix.com/man-page/linux/1/shuf/>.

- Randomize the order of lines in a file and output the result:

```bash
shuf filename
```

- Only output the first 5 entries of the result:

```bash
shuf --head-count=5 filename
```

- Write output to another file:

```bash
shuf filename --output=output_filename
```

- Generate random numbers in range 1-10:

```bash
shuf --input-range=1-10
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[SAURABH SHARMA](mailto:22629916+itsjzt@users.noreply.github.com) | shuf: add to osx platform (#2186) | 2018-07-17T09:45:44 | [214495567172](https://github.com/tldr-pages/tldr/commit/214495567172274f01405c5d14a8c2d33f7e6fb5)

