---
author: ['Stig124', 'Max Xu']
date: 1625841955
title: "cpufreq-info, TLDR Pages"
description: "cpufreq-info, A tool to show CPU frequency information."
categories: "linux"
---
> More information: <https://manned.org/cpufreq-info>.

- Show CPU frequency information for all CPUs:

```bash
cpufreq-info
```

- Show CPU frequency information for the specified CPU:

```bash
cpufreq-info -c cpu_number
```

- Show the allowed minimum and maximum CPU frequency:

```bash
cpufreq-info -l
```

- Show the current minimum and maximum CPU frequency and policy in table format:

```bash
cpufreq-info -o
```

- Show available CPU frequency policies:

```bash
cpufreq-info -g
```

- Show current CPU work frequency in a human-readable format, according to the cpufreq kernel module:

```bash
cpufreq-info -f -m
```

- Show current CPU work frequency in a human-readable format, by reading it from hardware (only available to root):

```bash
sudo cpufreq-info -w -m
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Max Xu](mailto:xuhuan@live.cn) | cpufreq-info: Update (#1866) | 2018-01-08T09:27:05 | [0ab26f049cb3](https://github.com/tldr-pages/tldr/commit/0ab26f049cb3b3cbfa930968aea3c3c529e02e60)
[Max Xu](mailto:xuhuan@live.cn) | cpufreq-info: add page (#1834) | 2017-12-28T20:41:00 | [329136bf60ba](https://github.com/tldr-pages/tldr/commit/329136bf60ba7b751835c8cfa8e9fe90b3d391fb)

