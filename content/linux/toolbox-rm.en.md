---
author: ['K.B.Dharun Krishna']
date: 1659684663
title: "toolbox rm"
description: "toolbox rm, Remove one or more `toolbox` containers."
categories: "linux"
---
> See also: `toolbox rmi`.

> More information: <https://manned.org/toolbox-rm.1>.

- Remove a toolbox container:

```bash
toolbox rm container_name
```

- Remove all `toolbox` containers:

```bash
toolbox rm --all
```

- Force the removal of a currently active `toolbox` container:

```bash
toolbox rm --force container_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | toolbox: add pages (#8280) | 2022-08-05T09:31:03 | [822a07003b21](https://github.com/tldr-pages/tldr/commit/822a07003b21f3050e53a19a44d6149a1736a9fe)

