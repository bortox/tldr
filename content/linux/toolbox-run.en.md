---
author: ['K.B.Dharun Krishna']
date: 1659684663
title: "toolbox run"
description: "toolbox run, Run a command in an existing `toolbox` container."
categories: "linux"
---
> See also: `toolbox enter`.

> More information: <https://manned.org/toolbox-run>.

- Run a command inside a specific `toolbox` container:

```bash
toolbox run --container container_name command
```

- Run a command inside a `toolbox` container for a specific release of a distribution:

```bash
toolbox run --distro distribution --release release command
```

- Run `emacs` inside a `toolbox` container using the default image for Fedora 36:

```bash
toolbox run --distro fedora --release f36 emacs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | toolbox: add pages (#8280) | 2022-08-05T09:31:03 | [822a07003b21](https://github.com/tldr-pages/tldr/commit/822a07003b21f3050e53a19a44d6149a1736a9fe)

