---
author: ['Arnaud Spiwack']
date: 1624649568
title: "pixiecore, TLDR Pages"
description: "pixiecore, Tool to manage the network booting of machines."
categories: "common"
---
> More information: <https://github.com/danderson/netboot/tree/master/pixiecore>.

- Start a PXE boot server which provides a `netboot.xyz` boot image:

```bash
pixiecore quick xyz --dhcp-no-bind
```

- Start a new PXE boot server which provides an Ubuntu boot image:

```bash
pixiecore quick ubuntu --dhcp-no-bind
```

- Get a list of all available boot images for quick mode:

```bash
pixiecore quick --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Arnaud Spiwack](mailto:arnaud@spiwack.net) | pixiecore: add page (#6094) | 2021-06-25T21:32:48 | [62d960c91429](https://github.com/tldr-pages/tldr/commit/62d960c91429695e86e112ec1466b0441d974fc0)

