---
author: ['Adam Herst']
date: 1624454553
title: "virsh pool-list, TLDR Pages"
description: "virsh pool-list, List information about virtual machine storage pools."
categories: "common"
---
> See also: `virsh`, `virsh-pool-autostart`, `virsh-pool-define-as`.

> More information: <https://manned.org/virsh>.

- List the name, state, and whether autostart is enabled or disabled for active storage pools:

```bash
virsh pool-list
```

- List information for active and inactive or just inactive storage pools:

```bash
virsh pool-list --all|inactive
```

- List extended information about persistence, capacity, allocation, and available space for active storage pools:

```bash
virsh pool-list --details
```

- List information for active storage pools with either autostart enabled or disabled:

```bash
virsh pool-list --autostart|no-autostart
```

- List information for active storage pools that are either persistent or transient:

```bash
virsh pool-list --persistent|transient
```

- List the name and UUID of active storage pools:

```bash
virsh pool-list --name --uuid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | Update virsh-pool-list.md | 2021-06-23T15:22:33 | [a4c8e4100796](https://github.com/tldr-pages/tldr/commit/a4c8e41007966f7b2734d03249fb69ccf66cecba)
[Adam Herst](mailto:adamherst@adamherst.com) | Update virsh-pool-list.md | 2021-06-23T15:22:33 | [9e2c31d3a17a](https://github.com/tldr-pages/tldr/commit/9e2c31d3a17a8ab888f1eaa08902d6050159147f)
[Adam Herst](mailto:adamherst@adamherst.com) | virsh-pool-*: add pages | 2021-06-23T15:22:33 | [882067d933b3](https://github.com/tldr-pages/tldr/commit/882067d933b3bdedb1e9729d1c4743c2e56581f3)

