---
author: ['Azrael JD', 'Shashank Shekhar']
date: 1643125787
title: "swapon, TLDR Pages"
description: "swapon, Enables device or file for swapping."
categories: "linux"
---
> More information: <https://manned.org/swapon>.

- Get swap information:

```bash
swapon -s
```

- Enable a given swap partition:

```bash
swapon /dev/sdb7
```

- Enable a given swap file:

```bash
swapon path/to/file
```

- Enable all swap areas:

```bash
swapon -a
```

- Enable swap by label of a device or file:

```bash
swapon -L swap1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | swapon: add more information link (#7706) | 2022-01-25T16:49:47 | [ed74535c79ae](https://github.com/tldr-pages/tldr/commit/ed74535c79aea9784d2b138712862d5c10ee68e8)
[Shashank Shekhar](mailto:correspond.shashank@gmail.com) | swapon: add page (#1996) | 2018-02-14T21:00:27 | [726b272e1287](https://github.com/tldr-pages/tldr/commit/726b272e1287d016d5722e5c73b686d94cd20823)

