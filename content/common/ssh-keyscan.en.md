---
author: ['Valentin Vetter', 'syleung', 'Starbeamrainbowlabs']
date: 1633351190
title: "ssh-keyscan, TLDR Pages"
description: "ssh-keyscan, Get the public ssh keys of remote hosts."
categories: "common"
---
> More information: <https://man.openbsd.org/ssh-keyscan>.

- Retrieve all public ssh keys of a remote host:

```bash
ssh-keyscan host
```

- Retrieve all public ssh keys of a remote host listening on a specific port:

```bash
ssh-keyscan -p port host
```

- Retrieve certain types of public ssh keys of a remote host:

```bash
ssh-keyscan -t rsa,dsa,ecdsa,ed25519 host
```

- Manually update the ssh known_hosts file with the fingerprint of a given host:

```bash
ssh-keyscan -H host >> ~/.ssh/known_hosts
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | ssh-keyscan: add known_hosts example (#3980) | 2020-05-02T03:05:41 | [b49de9b90e30](https://github.com/tldr-pages/tldr/commit/b49de9b90e301d01d4fe78f1d28c3cc8b0fb06a9)
[Valentin Vetter](mailto:BeLi4L@users.noreply.github.com) | ssh-keyscan: reformat arguments Co-Authored-By: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2019-09-08T17:11:19 | [763c0aeae5ad](https://github.com/tldr-pages/tldr/commit/763c0aeae5ad3b775a506b1d9773c50a6955e605)
[Valentin Vetter](mailto:BeLi4L@users.noreply.github.com) | ssh-keyscan: add page | 2019-09-08T17:11:19 | [85b8f04ca3b7](https://github.com/tldr-pages/tldr/commit/85b8f04ca3b70a4411b013c103f5cb342dbb00bc)

