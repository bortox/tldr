---
author: ['syleung', 'marchersimon']
date: 1633351190
title: "ssh-add"
description: "ssh-add, Manage loaded ssh keys in the ssh-agent."
categories: "common"
---
> Ensure that ssh-agent is up and running for the keys to be loaded in it.

> More information: <https://man.openbsd.org/ssh-add>.

- Add the default ssh keys in `~/.ssh` to the ssh-agent:

```bash
ssh-add
```

- Add a specific key to the ssh-agent:

```bash
ssh-add path/to/private_key
```

- List fingerprints of currently loaded keys:

```bash
ssh-add -l
```

- Delete a key from the ssh-agent:

```bash
ssh-add -d path/to/private_key
```

- Delete all currently loaded keys from the ssh-agent:

```bash
ssh-add -D
```

- Add a key to the ssh-agent and the keychain:

```bash
ssh-add -K path/to/private_key
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | feh, hostname, fc, ssh-add: move to common (#6487) | 2021-09-08T08:55:55 | [4ef097c3581a](https://github.com/tldr-pages/tldr/commit/4ef097c3581a5a5d6a740b23629e82852b59680c)

