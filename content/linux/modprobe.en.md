---
author: ['Lucas Gabriel Schneider', 'Starbeamrainbowlabs']
date: 1629110041
title: "modprobe"
description: "modprobe, Add or remove modules from the Linux kernel."
categories: "linux"
---
> More information: <https://manned.org/modprobe>.

- Pretend to load a module into the kernel, but don't actually do it:

```bash
sudo modprobe --dry-run module_name
```

- Load a module into the kernel:

```bash
sudo modprobe module_name
```

- Remove a module from the kernel:

```bash
sudo modprobe --remove module_name
```

- Remove a module and those that depend on it from the kernel:

```bash
sudo modprobe --remove-dependencies module_name
```

- Show a kernel module's dependencies:

```bash
sudo modprobe --show-depends module_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | modprobe: Add page (#2166) | 2018-07-05T18:13:16 | [45fec77380f5](https://github.com/tldr-pages/tldr/commit/45fec77380f5e328d0062588a4e6abb71442db56)

