---
author: ['michaeldel']
date: 1617492783
title: "encfs"
description: "encfs, Mounts or creates encrypted virtual filesystems."
categories: "common"
---
> See also `fusermount`, which can unmount filesystems mounted by this command.

> More information: <https://github.com/vgough/encfs>.

- Initialize or mount an encrypted filesystem:

```bash
encfs /path/to/cipher_dir /path/to/mount_point
```

- Initialize an encrypted filesystem with standard settings:

```bash
encfs --standard /path/to/cipher_dir /path/to/mount_point
```

- Run encfs in the foreground instead of spawning a daemon:

```bash
encfs -f /path/to/cipher_dir /path/to/mount_point
```

- Mount an encrypted snapshot of a plain directory:

```bash
encfs --reverse path/to/plain_dir path/to/cipher_dir
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[michaeldel](mailto:michaeldel@protonmail.com) | encfs: improve wording Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2021-04-04T01:33:03 | [65746eb5bb70](https://github.com/tldr-pages/tldr/commit/65746eb5bb7054d9e511daa52abe2c91c4131fe6)
[michaeldel](mailto:michaeldel@protonmail.com) | encfs: fix unmount example to comply with style | 2021-04-04T01:33:03 | [ea5a77b14c19](https://github.com/tldr-pages/tldr/commit/ea5a77b14c195af989ae30f16911495ad5ea6725)
[michaeldel](mailto:michaeldel@protonmail.com) | encfs: remove leading path slash Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> | 2021-04-04T01:33:03 | [6ff630845697](https://github.com/tldr-pages/tldr/commit/6ff6308456975819a804ff26e4dedcdae6fc40b8)
[michaeldel](mailto:michaeldel@protonmail.com) | encfs: add page | 2021-04-04T01:33:03 | [82e8a32d5c1f](https://github.com/tldr-pages/tldr/commit/82e8a32d5c1f13502dd70125b81e2858df06a832)

