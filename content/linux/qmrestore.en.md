---
author: ['Ein Verne']
date: 1635600193
title: "qmrestore"
description: "qmrestore, Restore QemuServer vzdump Backups."
categories: "linux"
---
> More information: <https://pve.proxmox.com/pve-docs/qmrestore.1.html>.

- Restore KVM-based virtual machine to local storage:

```bash
qmrestore /var/lib/vz/dump/backup_file.vma.lzo vm_id --storage local
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | qm, qmrestore: add page (#7157) | 2021-10-30T15:23:13 | [17c1e31309d3](https://github.com/tldr-pages/tldr/commit/17c1e31309d3a16f0ffccd215d683c947731700a)

