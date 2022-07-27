---
author: ['lbonanomi', 'Lucas Gabriel Schneider']
date: 1630607629
title: "ipcrm, TLDR Pages"
description: "ipcrm, Delete IPC (Inter-process Communication) resources."
categories: "linux"
---
> More information: <https://manned.org/ipcrm>.

- Delete a shared memory segment by ID:

```bash
ipcrm --shmem-id shmem_id
```

- Delete a shared memory segment by key:

```bash
ipcrm --shmem-key shmem_key
```

- Delete an IPC queue by ID:

```bash
ipcrm --queue-id ipc_queue_id
```

- Delete an IPC queue by key:

```bash
ipcrm --queue-key ipc_queue_key
```

- Delete a semaphore by ID:

```bash
ipcrm --semaphore-id semaphore_id
```

- Delete a semaphore by key:

```bash
ipcrm --semaphore-key semaphore_key
```

- Delete all IPC resources:

```bash
ipcrm --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | ipcrm: add page (#2974) | 2019-05-04T15:49:20 | [f1043cce7992](https://github.com/tldr-pages/tldr/commit/f1043cce7992fe49b0aee5d4d28e47489e5dd1db)

