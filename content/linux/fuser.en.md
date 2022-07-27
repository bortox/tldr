---
author: ['Stig124', 'Muhammad Falak R Wani', 'Miguel Mendes', 'Igor Shubovych', 'David Siefert']
date: 1657899197
title: "fuser, TLDR Pages"
description: "fuser, Display process IDs currently using files or sockets."
categories: "linux"
---
> More information: <https://manned.org/fuser>.

- Find which processes are accessing a file or directory:

```bash
fuser path/to/file_or_directory
```

- Show more fields (`USER`, `PID`, `ACCESS` and `COMMAND`):

```bash
fuser --verbose path/to/file_or_directory
```

- Identify processes using a TCP socket:

```bash
fuser --namespace tcp port
```

- Kill all processes accessing a file or directory (sends the `SIGKILL` signal):

```bash
fuser --kill path/to/file_or_directory
```

- Find which processes are accessing the filesystem containing a specific file or directory:

```bash
fuser --mount path/to/file_or_directory
```

- Kill all processes with a TCP connection on a specific port:

```bash
fuser --kill port/tcp
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | fuser: add example to kill processes bound to a specific socket (#8175) | 2022-07-15T17:33:17 | [91cd7a0be1de](https://github.com/tldr-pages/tldr/commit/91cd7a0be1defc6c6be4c72509ff3ce11d6fd0cb)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Miguel Mendes](mailto:mendesmiguel@users.noreply.github.com) | fuser: add new examples (#2513) | 2019-12-29T07:52:10 | [6fe6ed96410d](https://github.com/tldr-pages/tldr/commit/6fe6ed96410d945fece24c79fbc392ceccad68de)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | fuser: linting | 2016-01-18T23:18:06 | [f83d54567aef](https://github.com/tldr-pages/tldr/commit/f83d54567aef5f0e456607478e826db1d0979955)
[David Siefert](mailto:siefert.david@gmail.com) | fuser command | 2015-12-30T18:16:51 | [10bf3d17e996](https://github.com/tldr-pages/tldr/commit/10bf3d17e996ab5c4f19918d533a26074b5a4490)

