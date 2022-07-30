---
author: ['Rahul Kumar', 'Patrice Denis', 'Emily Grace Seville']
date: 1643317600
title: "groupadd"
description: "groupadd, Add user groups to the system."
categories: "linux"
---
> See also: `groups`, `groupdel`, `groupmod`.

> More information: <https://manned.org/groupadd>.

- Create a new group:

```bash
sudo groupadd group_name
```

- Create a new system group:

```bash
sudo groupadd --system group_name
```

- Create a new group with the specific groupid:

```bash
sudo groupadd --gid id group_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | groupadd, groupdel, groupmod, groups: update page (#7660) | 2022-01-27T22:06:40 | [3a104d86764f](https://github.com/tldr-pages/tldr/commit/3a104d86764f1ed69b9f0785f82f00e9dd451d7b)
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[Rahul Kumar](mailto:rahulcomp24@gmail.com) | groupadd, groupmod, groupdel: add page (#1194) | 2016-12-14T06:19:54 | [4b464d6a9cf3](https://github.com/tldr-pages/tldr/commit/4b464d6a9cf34c3bc73ceaaa3a75daa5c068de33)

