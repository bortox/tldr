---
author: ['Stig124', 'Max Xu', 'Agniva De Sarker']
date: 1625841955
title: "cpufreq-set, TLDR Pages"
description: "cpufreq-set, A tool to modify CPU frequency settings."
categories: "linux"
---
> The frequency value should range between the output of command `cpufreq-info -l`.

> More information: <https://manned.org/cpufreq-set>.

- Set the CPU frequency policy of CPU 1 to "userspace":

```bash
sudo cpufreq-set -c 1 -g userspace
```

- Set the current minimum CPU frequency of CPU 1:

```bash
sudo cpufreq-set -c 1 --min min_frequency
```

- Set the current maximum CPU frequency of CPU 1:

```bash
sudo cpufreq-set -c 1 --max max_frequency
```

- Set the current work frequency of CPU 1:

```bash
sudo cpufreq-set -c 1 -f work_frequency
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | cpufreq-set: clarify description | 2018-01-11T13:03:52 | [995d43b46aa4](https://github.com/tldr-pages/tldr/commit/995d43b46aa4526ea24086f82b790e64d628e22e)
[Max Xu](mailto:xuhuan@live.cn) | Update cpufreq-set.md | 2018-01-11T12:45:28 | [9c55758596c7](https://github.com/tldr-pages/tldr/commit/9c55758596c71717e61b7fc3c5f90bda4cd79db3)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | cpufreq-set: wrap in backticks | 2018-01-07T09:59:20 | [2fbd2598eb8f](https://github.com/tldr-pages/tldr/commit/2fbd2598eb8fd425f6df20b238fa7a93b1c9a764)
[Max Xu](mailto:xuhuan@live.cn) | cpufreq-set.md: add value range | 2018-01-06T09:20:02 | [512306ff26f9](https://github.com/tldr-pages/tldr/commit/512306ff26f918213350e9c9e2bc0251425afd5f)
[Max Xu](mailto:xuhuan@live.cn) | Update cpufreq-set.md | 2018-01-06T07:03:49 | [10f24962f175](https://github.com/tldr-pages/tldr/commit/10f24962f17545cac2296e612eed1b0d0cb4f3c6)
[Max Xu](mailto:xuhuan@live.cn) | cpufreq-set.md: add page | 2018-01-06T07:00:12 | [b293ccb7e2b6](https://github.com/tldr-pages/tldr/commit/b293ccb7e2b6beda6181eb717e15f6569bdf110c)

