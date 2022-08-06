---
author: ['K.B.Dharun Krishna']
date: 1659684663
title: "toolbox create"
description: "toolbox create, Create a new `toolbox` container."
categories: "linux"
---
> More information: <https://manned.org/toolbox-create.1>.

- Create a `toolbox` container for a specific distribution:

```bash
toolbox create --distro distribution
```

- Create a `toolbox` container for a specific release of the current distribution:

```bash
toolbox create --release release
```

- Create a `toolbox` container with a custom image:

```bash
toolbox create --image name
```

- Create a `toolbox` container from a custom Fedora image:

```bash
toolbox create --image registry.fedoraproject.org/fedora-toolbox:36
```

- Create a `toolbox` container using the default image for Fedora 36:

```bash
toolbox create --distro fedora --release f36
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | toolbox: add pages (#8280) | 2022-08-05T09:31:03 | [822a07003b21](https://github.com/tldr-pages/tldr/commit/822a07003b21f3050e53a19a44d6149a1736a9fe)

