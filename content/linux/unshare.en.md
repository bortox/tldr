---
author: ['Seth Falco']
date: 1648937996
title: "unshare, TLDR Pages"
description: "unshare, Execute a command in new user-defined namespaces."
categories: "linux"
---
> More information: <https://www.kernel.org/doc/html/latest/userspace-api/unshare.html>.

- Execute a command without sharing access to connected networks:

```bash
unshare --net command command_arguments
```

- Execute a command as a child process without sharing mounts, processes, or networks:

```bash
unshare --mount --pid --net --fork command command_arguments
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | unshare: add page (#7920) | 2022-04-03T00:19:56 | [487d901904c1](https://github.com/tldr-pages/tldr/commit/487d901904c179ce444b04a44a815fab2dfa7ca0)

