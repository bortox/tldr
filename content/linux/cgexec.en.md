---
author: ['Ray Voice']
date: 1634070497
title: "cgexec, TLDR Pages"
description: "cgexec, Limit, measure, and control resources used by processes."
categories: "linux"
---
> Multiple cgroup types (aka controllers) exist, such as `cpu`, `memory`, etc.

> More information: <https://manned.org/cgexec>.

- Execute a process in a given cgroup with given controller:

```bash
cgexec -g controller:cgroup_name process_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ray Voice](mailto:33094591+Ray6464@users.noreply.github.com) | cgexec: add page (#6767) | 2021-10-12T22:28:17 | [a8615b3e0bc1](https://github.com/tldr-pages/tldr/commit/a8615b3e0bc1a907d1ddafb3e74190daa3679891)

