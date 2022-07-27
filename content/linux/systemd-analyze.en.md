---
author: ['Sematre', 'Responsible', 'Ryan Lahfa', 'Seth Falco']
date: 1635016591
title: "systemd-analyze, TLDR Pages"
description: "systemd-analyze, Analyze and debug system manager."
categories: "linux"
---
> Show timing details about the boot process of units (services, mount points, devices, sockets).

> More information: <https://manned.org/systemd-analyze>.

- List time of each unit to start up:

```bash
systemd-analyze blame
```

- Print a tree of the time-critical chain of units:

```bash
systemd-analyze critical-chain
```

- Create an SVG file showing when each system service started, highlighting the time that they spent on initialization:

```bash
systemd-analyze plot > path/to/file.svg
```

- Plot a dependency graph and convert it to an SVG file:

```bash
systemd-analyze dot | dot -Tsvg > path/to/file.svg
```

- Show security scores of running units:

```bash
systemd-analyze security
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ryan Lahfa](mailto:masterancpp@gmail.com) | systemd-analyze: add security example, generalize scope of the tool, add link to manual page (#7161) | 2021-10-23T21:16:31 | [0106a441956c](https://github.com/tldr-pages/tldr/commit/0106a441956cae765ce3578c787c7134a7dc448c)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Sematre](mailto:Sematre@gmx.de) | systemd-analyze: Add examples for 'plot' and 'dot' (#5784) | 2021-04-18T17:28:12 | [743f7d7d4f4c](https://github.com/tldr-pages/tldr/commit/743f7d7d4f4c3a4fb92b806b46443cf90a0005ee)
[Responsible](mailto:responsible@users.noreply.github.com) | Update systemctl.md; add page of systemd-analyze (#844) | 2016-04-10T00:36:11 | [1bafef40fabb](https://github.com/tldr-pages/tldr/commit/1bafef40fabbf050b18eb767ac6b834635bf5610)

