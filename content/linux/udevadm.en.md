---
author: ['aos']
date: 1631311385
title: "udevadm"
description: "udevadm, Linux `udev` management tool."
categories: "linux"
---
> More information: <https://www.freedesktop.org/software/systemd/man/udevadm>.

- Monitor all device events:

```bash
sudo udevadm monitor
```

- Print `uevents` sent out by the kernel:

```bash
sudo udevadm monitor --kernel
```

- Print device events after being processed by `udev`:

```bash
sudo udevadm monitor --udev
```

- List attributes of a device:

```bash
sudo udevadm info --attribute-walk --path /dev/sda1
```

- Reload all `udev` rules:

```bash
sudo udevadm control --reload-rules
```

- Trigger all `udev` rules to run:

```bash
sudo udevadm trigger
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[aos](mailto:aosdab@gmail.com) | udevadm: add page (#6478) | 2021-09-11T00:03:05 | [b12696258044](https://github.com/tldr-pages/tldr/commit/b1269625804476c084633d752ef9f25a4a073b41)

