---
author: ['Emily Grace Seville']
date: 1644064395
title: "tail"
description: "tail, Display the last part of a file."
categories: "osx"
---
> See also: `head`.

> More information: <https://manned.org/man/freebsd-13.0/tail.1>.

- Show last 'count' lines in file:

```bash
tail -n count path/to/file
```

- Print a file from a specific line number:

```bash
tail -n +count path/to/file
```

- Print a specific count of bytes from the end of a given file:

```bash
tail -c count path/to/file
```

- Print the last lines of a given file and keep reading file until `Ctrl + C`:

```bash
tail -f path/to/file
```

- Keep reading file until `Ctrl + C`, even if the file is inaccessible:

```bash
tail -F path/to/file
```

- Show last 'count' lines in 'file' and refresh every 'seconds' seconds:

```bash
tail -n count -s seconds -f path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | tail: add page (#7688) | 2022-02-05T13:33:15 | [4f57bb181e53](https://github.com/tldr-pages/tldr/commit/4f57bb181e53d127039008eb01ad97704f125e7a)

