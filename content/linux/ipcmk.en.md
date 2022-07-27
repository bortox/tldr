---
author: ['lbonanomi', 'Lucas Gabriel Schneider', 'Ishaan Bhimwal']
date: 1658240132
title: "ipcmk, TLDR Pages"
description: "ipcmk, Create IPC (Inter-process Communication) resources."
categories: "linux"
---
> More information: <https://manned.org/ipcmk>.

- Create a shared memory segment:

```bash
ipcmk --shmem segment_size_in_bytes
```

- Create a semaphore:

```bash
ipcmk --semaphore element_size
```

- Create a message queue:

```bash
ipcmk --queue
```

- Create a shared memory segment with specific permissions (default is 0644):

```bash
ipcmk --shmem segment_size_in_bytes octal_permissions
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ishaan Bhimwal](mailto:ishaanbhimwal@protonmail.com) | linux/*: fix typos (#8227) | 2022-07-19T16:15:32 | [099ee2657117](https://github.com/tldr-pages/tldr/commit/099ee2657117da61e75d93ffae2c49690b4c8440)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | ipcmk: add page (#2973) | 2019-05-05T14:21:50 | [be3f9bb817da](https://github.com/tldr-pages/tldr/commit/be3f9bb817da7d88d994100dd8556a8f0cd873a9)

