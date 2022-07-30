---
author: ['bl-ue']
date: 1615467249
title: "chrt"
description: "chrt, Manipulate the real-time attributes of a process."
categories: "linux"
---
> More information: <https://man7.org/linux/man-pages/man1/chrt.1.html>.

- Display attributes of a process:

```bash
chrt --pid PID
```

- Display attributes of all threads of a process:

```bash
chrt --all-tasks --pid PID
```

- Display the min/max priority values that can be used with `chrt`:

```bash
chrt --max
```

- Set the scheduling policy for a process:

```bash
chrt --pid PID --deadline|idle|batch|rr|fifo|other
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | chrt: add page (#5398) | 2021-03-11T13:54:09 | [b13a5ddaaf5c](https://github.com/tldr-pages/tldr/commit/b13a5ddaaf5cce10851689c75fe76b4b35187cc7)

