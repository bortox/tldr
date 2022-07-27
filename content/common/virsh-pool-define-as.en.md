---
author: ['Adam Herst']
date: 1624454553
title: "virsh pool-define-as, TLDR Pages"
description: "virsh pool-define-as, Create a configuration file in `/etc/libvirt/storage` for a persistent virtual machine storage pool from the provided arguments."
categories: "common"
---
> See also: `virsh`, `virsh-pool-build`, `virsh-pool-start`.

> More information: <https://manned.org/virsh>.

- Create the configuration file for a storage pool called pool_name using `/var/vms` as the underlying storage system:

```bash
virsh pool-define-as --name pool_name --type dir --target /var/vms
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | Update virsh-pool-define-as.md | 2021-06-23T15:22:33 | [2c56ba03446e](https://github.com/tldr-pages/tldr/commit/2c56ba03446ecc6db22031b90c82922ed099970a)
[Adam Herst](mailto:adamherst@adamherst.com) | Update virsh-pool-define-as.md | 2021-06-23T15:22:33 | [4c5068c69e14](https://github.com/tldr-pages/tldr/commit/4c5068c69e145b5c5c67d6c49764ec9d16e6e84e)
[Adam Herst](mailto:adamherst@adamherst.com) | Update virsh-pool-define-as.md | 2021-06-23T15:22:33 | [710ab0193822](https://github.com/tldr-pages/tldr/commit/710ab019382218b1e55f6f401e5392b7308dad02)
[Adam Herst](mailto:adamherst@adamherst.com) | Update virsh-pool-define-as.md | 2021-06-23T15:22:33 | [f37935a46311](https://github.com/tldr-pages/tldr/commit/f37935a46311bdb1618d16cea63bc81d532544b2)
[Adam Herst](mailto:adamherst@adamherst.com) | virsh-pool-*: add pages | 2021-06-23T15:22:33 | [882067d933b3](https://github.com/tldr-pages/tldr/commit/882067d933b3bdedb1e9729d1c4743c2e56581f3)

