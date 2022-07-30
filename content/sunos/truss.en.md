---
author: ['lbonanomi', 'marchersimon']
date: 1617188954
title: "truss"
description: "truss, Troubleshooting tool for tracing system calls."
categories: "sunos"
---
> SunOS equivalent of strace.

> More information: <https://www.unix.com/man-page/linux/1/truss>.

- Start tracing a program by executing it, following all child processes:

```bash
truss -f program
```

- Start tracing a specific process by its PID:

```bash
truss -p pid
```

- Start tracing a program by executing it, showing arguments and environment variables:

```bash
truss -a -e program
```

- Count time, calls, and errors for each system call and report a summary on program exit:

```bash
truss -c -p pid
```

- Trace a process filtering output by system call:

```bash
truss -p pid -t system_call_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | sunos/*: add more information link (#5649) | 2021-03-31T13:09:14 | [d12aac42e8d5](https://github.com/tldr-pages/tldr/commit/d12aac42e8d5a4f35d0766c0cd5127ab76b6dc76)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | truss: add page (#2907) | 2019-04-15T00:51:21 | [452beb4e157a](https://github.com/tldr-pages/tldr/commit/452beb4e157ab2dfa2c13ea5a824dda650827a64)

