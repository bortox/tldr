---
author: ['Axel Navarro']
date: 1633282024
title: "csrutil, TLDR Pages"
description: "csrutil, Manage the System Integrity Protection configuration."
categories: "osx"
---
> More information: <https://ss64.com/osx/csrutil.html>.

- Display the System Integrity Protection status:

```bash
csrutil status
```

- Disable the System Integrity Protection:

```bash
csrutil disable
```

- Enable the System Integrity Protection:

```bash
csrutil enable
```

- Display the list of allowed NetBoot sources:

```bash
csrutil netboot list
```

- Add an IPv4 address to the list of allowed NetBoot sources:

```bash
csrutil netboot add ip_address
```

- Reset the System Integrity Protection status and clear the NetBoot list:

```bash
csrutil clear
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | csrutil: add page (#6615) | 2021-10-03T19:27:04 | [41310d3449b4](https://github.com/tldr-pages/tldr/commit/41310d3449b430c550e0fec5872a7bb9f3523e83)

