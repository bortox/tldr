---
author: ['Yoshinari Takaoka', 'Emily Grace Seville', 'matugm', 'Agniva De Sarker', 'Kyle Sweeney', 'lord63', 'Guido Lena Cota', 'Ruben Vereecken', 'Adam Dobrawy']
date: 1647882468
title: "strace"
description: "strace, Troubleshooting tool for tracing system calls."
categories: "linux"
---
> More information: <https://manned.org/strace>.

- Start tracing a specific process by its PID:

```bash
strace -p pid
```

- Trace a process and filter output by system call:

```bash
strace -p pid -e system_call_name
```

- Count time, calls, and errors for each system call and report a summary on program exit:

```bash
strace -p pid -c
```

- Show the time spent in every system call:

```bash
strace -p pid -T
```

- Start tracing a program by executing it:

```bash
strace program
```

- Start tracing file operations of a program:

```bash
strace -e trace=file program
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mass change: apply snake case to tokens (#2518) | 2018-10-29T12:14:25 | [18370557b25e](https://github.com/tldr-pages/tldr/commit/18370557b25e5340d9ee5cfeee346ce8fcb4ef95)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | strace: fix syntax | 2018-01-01T16:36:51 | [a98398f68d64](https://github.com/tldr-pages/tldr/commit/a98398f68d64ef45ab63dbe153f5fec4b822a7f3)
[Adam Dobrawy](mailto:ad-m@users.noreply.github.com) | [strace] Add example of tracing file operations | 2018-01-01T13:21:56 | [911b777839ab](https://github.com/tldr-pages/tldr/commit/911b777839ab534cbaed15db369f492b96aa3d55)
[Kyle Sweeney](mailto:KyleMDSweeney@gmail.com) | strace.md: Added option to start an executable (#979) * updated strace.md with starting a program * fixed errors, and followed same `` [...] | 2016-08-22T13:59:39 | [111d8aae0fad](https://github.com/tldr-pages/tldr/commit/111d8aae0fadd415829920fc55d5beaf1cfdd7c2)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Yoshinari Takaoka](mailto:mumumu@mumumu.org) | strace: add -T example | 2016-01-03T19:17:07 | [c016a93b7bab](https://github.com/tldr-pages/tldr/commit/c016a93b7babc5eee3177a3b4df9215de60aef25)
[lord63](mailto:lord63.j@gmail.com) | Fix markdown lint warning for linux man pages | 2015-10-22T09:00:05 | [1d2d523b2138](https://github.com/tldr-pages/tldr/commit/1d2d523b21388c959e70b5037641b57b9e50a39a)
[matugm](mailto:matugm@gmail.com) | Update strace | 2015-03-21T02:02:35 | [9b769653331e](https://github.com/tldr-pages/tldr/commit/9b769653331ed8cc4edc8dbc9ebe0386c3937af8)
[matugm](mailto:matugm@gmail.com) | Add strace | 2015-03-21T01:01:05 | [26e664ffcd51](https://github.com/tldr-pages/tldr/commit/26e664ffcd510728150d56ca83e7d1c5a335b527)

