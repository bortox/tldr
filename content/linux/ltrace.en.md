---
author: ['Terka Slan', 'sebastientinel', 'Igor Shubovych', 'marchersimon']
date: 1618584134
title: "ltrace"
description: "ltrace, Display dynamic library calls of a process."
categories: "linux"
---
> More information: <https://manned.org/ltrace>.

- Print (trace) library calls of a program binary:

```bash
ltrace ./program
```

- Count library calls. Print a handy summary at the bottom:

```bash
ltrace -c path/to/program
```

- Trace calls to malloc and free, omit those done by libc:

```bash
ltrace -e malloc+free-@libc.so* path/to/program
```

- Write to file instead of terminal:

```bash
ltrace -o file path/to/program
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | ltrace: linting | 2016-01-20T01:37:56 | [7e4ac4d8ef5e](https://github.com/tldr-pages/tldr/commit/7e4ac4d8ef5e721bc9dde3e213499aaf7d190b3e)
[Terka Slan](mailto:terezia.slaninakova@gmail.com) | Add ltrace Corrected the syntax Changed naming and formatting Changed naming Squashed the commits Add ltrace | 2016-01-20T01:33:55 | [5b3660214930](https://github.com/tldr-pages/tldr/commit/5b3660214930332a37d485b4e3ac83d911d70635)

