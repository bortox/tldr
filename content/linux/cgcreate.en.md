---
author: ['Ray Voice']
date: 1636444438
title: "cgcreate, TLDR Pages"
description: "cgcreate, Create cgroups, used to limit, measure, and control resources used by processes."
categories: "linux"
---
> `cgroups` types can be `memory`, `cpu`, `net_cls`, etc.

> More information: <https://manned.org/cgcreate>.

- Create a new group:

```bash
cgcreate -g group_type:group_name
```

- Create a new group with multiple cgroup types:

```bash
cgcreate -g group_type1,group_type2:group_name
```

- Create a subgroup:

```bash
mkdir /sys/fs/cgroup/group_type/group_name/subgroup_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ray Voice](mailto:33094591+Ray6464@users.noreply.github.com) | cgcreate: add page (#6768) | 2021-11-09T08:53:58 | [30e7368b30f1](https://github.com/tldr-pages/tldr/commit/30e7368b30f1260cd50d99d57f9f526f31330727)

