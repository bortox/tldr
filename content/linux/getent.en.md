---
author: ['Stig124', 'slash3b', 'Balázs Úr', 'slamp']
date: 1625841955
title: "getent, TLDR Pages"
description: "getent, Get entries from Name Service Switch libraries."
categories: "linux"
---
> More information: <https://manned.org/getent>.

- Get list of all groups:

```bash
getent group
```

- See the members of a group:

```bash
getent group group_name
```

- Get list of all services:

```bash
getent services
```

- Find a username by UID:

```bash
getent passwd 1000
```

- Perform a reverse DNS lookup:

```bash
getent hosts host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[slamp](mailto:slaamp@gmail.com) | correct typo getent group (#2634) | 2018-12-04T22:16:17 | [0bd703d8eaba](https://github.com/tldr-pages/tldr/commit/0bd703d8eaba5c0d7313ad99190f3bb5f0612296)
[slash3b](mailto:slash3b@gmail.com) | getent command was added | 2016-02-21T15:23:08 | [5de5f06ffb64](https://github.com/tldr-pages/tldr/commit/5de5f06ffb644b3cd35846127e571a007030ae80)

