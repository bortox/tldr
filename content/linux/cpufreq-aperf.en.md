---
author: ['Stig124', 'Max Xu', 'Seth Falco']
date: 1629050349
title: "cpufreq-aperf, TLDR Pages"
description: "cpufreq-aperf, Calculate the average CPU frequency over a time period."
categories: "linux"
---
> Requires root privileges.

> More information: <https://manned.org/cpufreq-aperf>.

- Start calculating, defaulting to all CPU cores and 1 second refresh interval:

```bash
sudo cpufreq-aperf
```

- Start calculating for CPU 1 only:

```bash
sudo cpufreq-aperf -c 1
```

- Start calculating with a 3 second refresh interval for all CPU cores:

```bash
sudo cpufreq-aperf -i 3
```

- Calculate only once:

```bash
sudo cpufreq-aperf -o
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Max Xu](mailto:xuhuan@live.cn) | cpufreq-aperf: add page (#1865) | 2018-01-08T13:02:34 | [7c9e7aafe14c](https://github.com/tldr-pages/tldr/commit/7c9e7aafe14c2ad63e7a93c0345071acefd62a58)

