---
author: ['Axel Navarro']
date: 1631091535
title: "needrestart"
description: "needrestart, Check which daemons need to be restarted after library upgrades."
categories: "linux"
---
> More information: <https://github.com/liske/needrestart>.

- List outdated processes:

```bash
needrestart
```

- Interactively restart services:

```bash
sudo needrestart
```

- List outdated processes in [v]erbose or [q]uiet mode:

```bash
needrestart -v|q
```

- Check if the [k]ernel is outdated:

```bash
needrestart -k
```

- Check if the CPU microcode is outdated:

```bash
needrestart -w
```

- List outdated processes in [b]atch mode:

```bash
needrestart -b
```

- List outdated processed using a specific [c]onfiguration file:

```bash
needrestart -c path/to/config
```

- Display help:

```bash
needrestart --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | needrestart: add page (#6417) | 2021-09-08T10:58:55 | [a9ab617ca1bf](https://github.com/tldr-pages/tldr/commit/a9ab617ca1bf47e0d58f907b9c17887181acd24a)

