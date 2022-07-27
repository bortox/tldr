---
author: ['Adam Herst']
date: 1624454553
title: "virsh pool-start, TLDR Pages"
description: "virsh pool-start, Start a previously configured but inactive virtual machine storage pool."
categories: "common"
---
> See also: `virsh`, `virsh-pool-define-as`, `virsh-pool-destroy`.

> More information: <https://manned.org/virsh>.

- Start the storage pool specified by name or UUID (determine using `virsh pool-list`) and create the underlying storage system if it doesn't exist:

```bash
virsh pool-start --pool name|uuid --build
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | Update virsh-pool-start.md | 2021-06-23T15:22:33 | [6945451307f7](https://github.com/tldr-pages/tldr/commit/6945451307f7b004365084811a10513bb22ec0b7)
[Adam Herst](mailto:adamherst@adamherst.com) | Update pages/common/virsh-pool-start.md Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-06-23T15:22:33 | [7c85feaad5d6](https://github.com/tldr-pages/tldr/commit/7c85feaad5d6c3ff936aacacb9926fbc5baa8d43)
[Adam Herst](mailto:adamherst@adamherst.com) | Update virsh-pool-start.md | 2021-06-23T15:22:33 | [41edb02bcbe0](https://github.com/tldr-pages/tldr/commit/41edb02bcbe026dcc37d32096e8ff2dc7bbb06e7)
[Adam Herst](mailto:adamherst@adamherst.com) | virsh-pool-*: add pages | 2021-06-23T15:22:33 | [882067d933b3](https://github.com/tldr-pages/tldr/commit/882067d933b3bdedb1e9729d1c4743c2e56581f3)

