---
author: ['Emanuele Rocca', 'Anton Karmanov']
date: 1635180060
title: "debootstrap"
description: "debootstrap, Create a basic Debian system."
categories: "linux"
---
> More information: <https://wiki.debian.org/Debootstrap>.

- Create a Debian stable release system inside the `debian-root` directory:

```bash
sudo debootstrap stable path/to/debian-root/ http://deb.debian.org/debian
```

- Create a minimal system including only required packages:

```bash
sudo debootstrap --variant=minbase stable path/to/debian-root/
```

- Create an Ubuntu 20.04 system inside the `focal-root` directory with a local mirror:

```bash
sudo debootstrap focal path/to/focal-root/ file:///path/to/mirror/
```

- Switch to a bootstrapped system:

```bash
sudo chroot path/to/root
```

- List available releases:

```bash
ls /usr/share/debootstrap/scripts/
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emanuele Rocca](mailto:ema@linux.it) | debootstrap: add --variant example (#7223) | 2021-10-25T18:41:00 | [1e44908607b2](https://github.com/tldr-pages/tldr/commit/1e44908607b21295a542decb9b255fa85900f1e7)
[Anton Karmanov](mailto:a.karmanov@inventati.org) | debootstrap: add page (#4971) | 2020-11-27T02:12:26 | [a1cf7408bfb9](https://github.com/tldr-pages/tldr/commit/a1cf7408bfb9f75647eccf28ff75e7fa9764f37a)

