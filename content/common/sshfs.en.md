---
author: ['Waldir Pimenta', 'Like-all', 'Borek Bernard', 'pxgamer', 'Tevfik U. Dincer', 'Seth Falco', 'Ruben Vereecken']
date: 1656325392
title: "sshfs"
description: "sshfs, Filesystem client based on SSH."
categories: "common"
---
> More information: <https://github.com/libfuse/sshfs>.

- Mount remote directory:

```bash
sshfs username@remote_host:remote_directory mountpoint
```

- Unmount remote directory:

```bash
umount mountpoint
```

- Mount remote directory from server with specific port:

```bash
sshfs username@remote_host:remote_directory -p 2222
```

- Use compression:

```bash
sshfs username@remote_host:remote_directory -C
```

- Follow symbolic links:

```bash
sshfs -o follow_symlinks username@remote_host:remote_directory mountpoint
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | sshfs: add link to homepage | 2019-05-29T14:41:10 | [0d16fc52987e](https://github.com/tldr-pages/tldr/commit/0d16fc52987e155b24e1f46360635407254908d8)
[Borek Bernard](mailto:borekb@gmail.com) | sshfs: use umount instead of fusermount (#2230) | 2018-07-29T17:53:47 | [6274f563f30d](https://github.com/tldr-pages/tldr/commit/6274f563f30d430059e7f979dd555c1b89d1fc43)
[Tevfik U. Dincer](mailto:udincer@users.noreply.github.com) | sshfs: Added follow symbolic links This is not obvious in the man page, and is very useful. | 2018-07-10T06:01:55 | [6f3d5999b7a8](https://github.com/tldr-pages/tldr/commit/6f3d5999b7a81b2a504a6ad3b6d5772e5cdae15d)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | page format: lowercase command names consistently (#1083) | 2016-09-22T09:03:38 | [107248374447](https://github.com/tldr-pages/tldr/commit/1072483744475ab5a25c87e8eb7ed10c99dd6ed8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Like-all](mailto:like-all@yandex.com) | common: sshfs | 2014-09-11T13:28:06 | [6afbe09945be](https://github.com/tldr-pages/tldr/commit/6afbe09945be06c7d1448a03400cb55f4a7a26ab)

