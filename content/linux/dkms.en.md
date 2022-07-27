---
author: ['Samuel']
date: 1606896758
title: "dkms, TLDR Pages"
description: "dkms, A framework that allows for dynamic building of kernel modules."
categories: "linux"
---
> More information: <https://github.com/dell/dkms>.

- List currently installed modules:

```bash
dkms status
```

- Rebuild all modules for the currently running kernel:

```bash
dkms autoinstall
```

- Install version 1.2.1 of the acpi_call module for the currently running kernel:

```bash
dkms install -m acpi_call -v 1.2.1
```

- Remove version 1.2.1 of the acpi_call module from all kernels:

```bash
dkms remove -m acpi_call -v 1.2.1 --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Samuel](mailto:samuel.woon@protonmail.com) | dkms: add page (#4997) | 2020-12-02T09:12:38 | [b0ef7f61b271](https://github.com/tldr-pages/tldr/commit/b0ef7f61b271b1b57a1f25b332dbcee2caeb4694)

