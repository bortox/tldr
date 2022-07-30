---
author: ['Adam Herst']
date: 1624454553
title: "virsh pool-autostart"
description: "virsh pool-autostart, Enable or disable autostart for a virtual machine storage pool."
categories: "common"
---
> See also: `virsh`.

> More information: <https://manned.org/virsh>.

- Enable autostart for the storage pool specified by name or UUID (determine using `virsh pool-list`):

```bash
virsh pool-autostart --pool name|uuid
```

- Disable autostart for the storage pool specified by name or UUID:

```bash
virsh pool-autostart --pool name|uuid --disable
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | Update pages/common/virsh-pool-autostart.md Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-06-23T15:22:33 | [e0746611da81](https://github.com/tldr-pages/tldr/commit/e0746611da81cb837e151488ddff39007778d612)
[Adam Herst](mailto:adamherst@adamherst.com) | Update virsh-pool-autostart.md | 2021-06-23T15:22:33 | [295424276b4e](https://github.com/tldr-pages/tldr/commit/295424276b4e2bb32097e5ef1d63d80956a87b2a)
[Adam Herst](mailto:adamherst@adamherst.com) | virsh-pool-*: add pages | 2021-06-23T15:22:33 | [882067d933b3](https://github.com/tldr-pages/tldr/commit/882067d933b3bdedb1e9729d1c4743c2e56581f3)

