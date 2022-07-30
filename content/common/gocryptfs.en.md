---
author: ['Schneider', 'Raffaele Mignone', 'Marco Bonelli']
date: 1559564381
title: "gocryptfs"
description: "gocryptfs, Encrypted overlay filesystem written in Go."
categories: "common"
---
> More information: <https://github.com/rfjakob/gocryptfs>.

- Initialize an encrypted filesystem:

```bash
gocryptfs -init path/to/cipher_dir
```

- Mount an encrypted filesystem:

```bash
gocryptfs path/to/cipher_dir path/to/mount_point
```

- Mount with the explicit master key instead of password:

```bash
gocryptfs --masterkey path/to/cipher_dir path/to/mount_point
```

- Change the password:

```bash
gocryptfs --passwd path/to/cipher_dir
```

- Make an encrypted snapshot of a plain directory:

```bash
gocryptfs --reverse path/to/plain_dir path/to/cipher_dir
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | gocryptfs.md add homepage | 2019-04-11T09:49:15 | [ccc0fe190140](https://github.com/tldr-pages/tldr/commit/ccc0fe190140aecefc5b326777100688f98b9e1a)
[Raffaele Mignone](mailto:raffy.m.96@gmail.com) | gocryptfs: add page (#2461) | 2018-10-24T09:19:41 | [0e1256b24454](https://github.com/tldr-pages/tldr/commit/0e1256b2445404520af560633ebdc5f3c41e687e)

