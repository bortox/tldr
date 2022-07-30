---
author: ['kevlu8']
date: 1635474650
title: "diskpart"
description: "diskpart, Disk, volume and partition manager."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/diskpart>.

- Run diskpart by itself in an administrative command prompt to enter its command line:

```bash
diskpart
```

- List all disks:

```bash
list disk
```

- Select a volume:

```bash
select volume volume
```

- Assign a drive letter to the selected volume:

```bash
assign letter letter
```

- Create a new partition:

```bash
create partition primary
```

- Activate the selected volume:

```bash
active
```

- Exit diskpart:

```bash
exit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[kevlu8](mailto:69993704+kevlu8@users.noreply.github.com) | diskpart: add page (#7091) | 2021-10-29T04:30:50 | [f4c9616601e0](https://github.com/tldr-pages/tldr/commit/f4c9616601e03e02a9a7d65d966300fa72b6c10b)

