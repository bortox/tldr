---
author: ['Stig124', 'Agniva De Sarker', 'Vincent Yang']
date: 1625841955
title: "foreman, TLDR Pages"
description: "foreman, Manage Procfile-based applications."
categories: "linux"
---
> More information: <https://manned.org/foreman>.

- Start an application with the Procfile in the current directory:

```bash
foreman start
```

- Start an application with a specified Procfile:

```bash
foreman start -f Procfile
```

- Start a specific application:

```bash
foreman start process
```

- Validate Procfile format:

```bash
foreman check
```

- Run one-off commands with the process's environment:

```bash
foreman run command
```

- Start all processes except the one named "worker":

```bash
foreman start -m all=1,worker=0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | foreman: update page - Put double quotes around worker - Wrap worker in tokens in the example | 2017-10-18T19:45:49 | [868954c0b434](https://github.com/tldr-pages/tldr/commit/868954c0b43423a3d24253ebf1daa4e47319e978)
[Vincent Yang](mailto:VincentYang2014@gmail.com) | Updated foreman grammar | 2017-10-15T05:58:16 | [80a1fa5ef3db](https://github.com/tldr-pages/tldr/commit/80a1fa5ef3dbbf90a90fd991f1684f36505b5e67)
[Vincent Yang](mailto:VincentYang2014@gmail.com) | Add specific Procfile option for foreman | 2017-10-08T01:39:03 | [093886e58708](https://github.com/tldr-pages/tldr/commit/093886e587087bf0f148716a75e65eefcaf0c425)
[Vincent Yang](mailto:VincentYang2014@gmail.com) | Updated docs | 2017-10-07T20:54:14 | [e0c5f8cc4521](https://github.com/tldr-pages/tldr/commit/e0c5f8cc4521fafa6ea74decc38ca9fdce73b225)
[Vincent Yang](mailto:VincentYang2014@gmail.com) | foreman | 2017-10-07T11:02:51 | [f434c6ebfa9c](https://github.com/tldr-pages/tldr/commit/f434c6ebfa9cf8c050a7b5c8e4f465b6d57cd0c2)

