---
author: ['Lucas Gabriel Schneider', 'Starbeamrainbowlabs', 'Laurent Indermühle']
date: 1630607629
title: "hostnamectl"
description: "hostnamectl, Get or set the hostname of the computer."
categories: "linux"
---
> More information: <https://manned.org/hostnamectl>.

- Get the hostname of the computer:

```bash
hostnamectl
```

- Set the hostname of the computer:

```bash
sudo hostnamectl set-hostname "hostname"
```

- Set a pretty hostname for the computer:

```bash
sudo hostnamectl set-hostname --static "hostname.example.com" && sudo hostnamectl set-hostname --pretty "hostname"
```

- Reset hostname to its default value:

```bash
sudo hostnamectl set-hostname --pretty ""
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Laurent Indermühle](mailto:honiix@pm.me) | hostnamectl: add --pretty and --static examples (#5203) | 2021-01-30T22:00:35 | [7c6dfb6d5566](https://github.com/tldr-pages/tldr/commit/7c6dfb6d55667fd5d556c13e6afd465986978ded)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | New command: hostnamectl | 2017-05-07T13:41:41 | [8125f34ee7ff](https://github.com/tldr-pages/tldr/commit/8125f34ee7ffaaf31d95aaefa3f10080f0613bdb)

