---
author: ['Josa Gesell', 'Agniva De Sarker', 'syleung']
date: 1633351190
title: "ssh-copy-id, TLDR Pages"
description: "ssh-copy-id, Install your public key in a remote machine's authorized_keys."
categories: "common"
---
> More information: <https://manned.org/ssh-copy-id>.

- Copy your keys to the remote machine:

```bash
ssh-copy-id username@remote_host
```

- Copy the given public key to the remote:

```bash
ssh-copy-id -i path/to/certificate username@remote_host
```

- Copy the given public key to the remote with specific port:

```bash
ssh-copy-id -i path/to/certificate -p port username@remote_host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | ssh-copy-id: Remove default key example | 2017-02-25T13:19:50 | [abd52f0ce826](https://github.com/tldr-pages/tldr/commit/abd52f0ce82634ad9d10859e946095a59d962930)
[Josa Gesell](mailto:josa@gesell.me) | ssh-copy-id: move to common | 2017-02-25T13:19:50 | [65f45a151700](https://github.com/tldr-pages/tldr/commit/65f45a1517006a69f5bcd80244d74bae47888deb)

