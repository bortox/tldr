---
author: ['sebastientinel', 'pxgamer', 'Vivek Krishnakumar']
date: 1603905583
title: "mosh"
description: "mosh, Mobile Shell (`mosh`) is a robust and responsive replacement for SSH."
categories: "common"
---
> `mosh` persists connections to remote servers while roaming between networks.

> More information: <https://mosh.org>.

- Connect to a remote server:

```bash
mosh username@remote_host
```

- Connect to a remote server with a specific identity (private key):

```bash
mosh --ssh="ssh -i path/to/key_file" username@remote_host
```

- Connect to a remote server using a specific port:

```bash
mosh --ssh="ssh -p 2222" username@remote_host
```

- Run a command on a remote server:

```bash
mosh remote_host -- command -with -flags
```

- Select Mosh UDP port (useful when `{{remote_host}}` is behind a NAT):

```bash
mosh -p 124 username@remote_host
```

- Usage when `mosh-server` binary is outside standard path:

```bash
mosh --server=path/to/bin/mosh-server remote_host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[pxgamer](mailto:owzie123@gmail.com) | mosh: add link to homepage | 2019-06-04T21:29:40 | [f3e57f20a5f3](https://github.com/tldr-pages/tldr/commit/f3e57f20a5f3f6a81e2c3c08c68f996300a18b2f)
[Vivek Krishnakumar](mailto:vkrishna@jcvi.org) | mosh: add page (#1384) | 2017-05-24T08:33:32 | [db766044deb1](https://github.com/tldr-pages/tldr/commit/db766044deb11523ae75401e0185be66af045dd0)

