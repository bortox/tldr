---
author: ['K.B.Dharun Krishna']
date: 1659684663
title: "toolbox enter"
description: "toolbox enter, Enter a `toolbox` container for interactive use."
categories: "linux"
---
> See also: `toolbox run`.

> More information: <https://manned.org/toolbox-enter.1>.

- Enter a `toolbox` container using the default image of a specific distribution:

```bash
toolbox enter --distro distribution
```

- Enter a `toolbox` container using the default image of a specific release of the current distribution:

```bash
toolbox enter --release release
```

- Enter a toolbox container using the default image for Fedora 36:

```bash
toolbox enter --distro fedora --release f36
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | toolbox: add pages (#8280) | 2022-08-05T09:31:03 | [822a07003b21](https://github.com/tldr-pages/tldr/commit/822a07003b21f3050e53a19a44d6149a1736a9fe)

