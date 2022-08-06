---
author: ['K.B.Dharun Krishna']
date: 1659684663
title: "toolbox rmi"
description: "toolbox rmi, Remove one or more `toolbox` images."
categories: "linux"
---
> See also: `toolbox rm`.

> More information: <https://manned.org/toolbox-rmi.1>.

- Remove a `toolbox` image:

```bash
toolbox rmi image_name
```

- Remove all `toolbox` images:

```bash
toolbox rmi --all
```

- Force the removal of a `toolbox` image which is currently being used by a container (the container will be removed as well):

```bash
toolbox rmi --force image_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | toolbox: add pages (#8280) | 2022-08-05T09:31:03 | [822a07003b21](https://github.com/tldr-pages/tldr/commit/822a07003b21f3050e53a19a44d6149a1736a9fe)

