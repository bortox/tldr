---
author: ['Axel Navarro', 'rooty']
date: 1647714509
title: "rmmod, TLDR Pages"
description: "rmmod, Remove modules from the Linux kernel."
categories: "linux"
---
> More information: <https://manned.org/rmmod>.

- Remove a module from the kernel:

```bash
sudo rmmod module_name
```

- Remove a module from the kernel and display verbose information:

```bash
sudo rmmod --verbose module_name
```

- Remove a module from the kernel and send errors to syslog instead of standard error:

```bash
sudo rmmod --syslog module_name
```

- Display help:

```bash
rmmod --help
```

- Display version:

```bash
rmmod --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[rooty](mailto:84267917+rootremoval@users.noreply.github.com) | rmmod: fix examples (#7879) | 2022-03-19T19:28:29 | [fada0e54ce3e](https://github.com/tldr-pages/tldr/commit/fada0e54ce3e9375f7a567d3baad9dd83b6e7189)
[Axel Navarro](mailto:navarroaxel@gmail.com) | rmmod: add page (#7106) | 2021-10-21T04:32:47 | [6fddf10ed916](https://github.com/tldr-pages/tldr/commit/6fddf10ed916cec0a86d5570ea9519fb3b5c24db)

