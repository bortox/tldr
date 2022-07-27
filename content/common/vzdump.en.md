---
author: ['Ein Verne']
date: 1636404924
title: "vzdump, TLDR Pages"
description: "vzdump, Backup Utility for virtual machines and containers."
categories: "common"
---
> More information: <https://pve.proxmox.com/pve-docs/vzdump.1.html>.

- Dump a guest virtual machine into the default dump directory (usually `/var/lib/vz/dump/`), excluding snapshots:

```bash
vzdump vm_id
```

- Back up the guest virtual machines with the IDs 101, 102, and 103:

```bash
vzdump 101 102 103
```

- Dump a guest virtual machine using a specific mode:

```bash
vzdump vm_id --mode suspend|snapshot
```

- Back up all guest systems and send an notification email to the root and admin users:

```bash
vzdump --all --mode suspend --mailto root --mailto admin
```

- Use snapshot mode (no downtime required) and a non-default dump directory:

```bash
vzdump vm_id --dumpdir path/to/directory --mode snapshot
```

- Back up all guest virtual machines excluding the IDs 101 and 102:

```bash
vzdump --mode suspend --exclude 101, 102
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | vzdump: add page (#7125) | 2021-11-08T21:55:24 | [49265db659e9](https://github.com/tldr-pages/tldr/commit/49265db659e9d8b59f941f6ee6c6be71e2b3111c)

