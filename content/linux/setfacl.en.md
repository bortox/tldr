---
author: ['alirezaghey', 'touhonoob', 'Emily Grace Seville']
date: 1647882468
title: "setfacl"
description: "setfacl, Set file access control lists (ACL)."
categories: "linux"
---
> More information: <https://manned.org/setfacl>.

- Modify ACL of a file for user with read and write access:

```bash
setfacl -m u:username:rw file
```

- Modify default ACL of a file for all users:

```bash
setfacl -d -m u::rw file
```

- Remove ACL of a file for a user:

```bash
setfacl -x u:username file
```

- Remove all ACL entries of a file:

```bash
setfacl -b file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[alirezaghey](mailto:26653424+alirezaghey@users.noreply.github.com) | setfacl: fix typo (#6340) for reference https://english.stackexchange.com/questions/105116/is-it-a-user-or-an-user | 2021-08-12T20:23:20 | [ffdee7822118](https://github.com/tldr-pages/tldr/commit/ffdee78221181d975d6cf26b3a56b94debc04e5d)
[touhonoob](mailto:touhonoob@gmail.com) | setfacl: add acronym to description | 2016-12-13T19:04:39 | [d501320e35cf](https://github.com/tldr-pages/tldr/commit/d501320e35cffa2adc804f43b6bb8a0edccc81ba)
[touhonoob](mailto:touhonoob@gmail.com) | setfacl: add page | 2016-12-13T19:04:39 | [2b28fea2626c](https://github.com/tldr-pages/tldr/commit/2b28fea2626c73aa02c4f97b38c9fc1a1de28ca5)

