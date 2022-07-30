---
author: ['slash3b', 'Peter Tripp', 'Shivam Mevawala', 'Marco Bonelli', 'Juri', 'CleanMachine1']
date: 1655819988
title: "sftp"
description: "sftp, Secure File Transfer Program."
categories: "common"
---
> Interactive program to copy files between hosts over SSH.

> For non-interactive file transfers, see `scp` or `rsync`.

> More information: <https://manned.org/sftp>.

- Connect to a remote server and enter an interactive command mode:

```bash
sftp remote_user@remote_host
```

- Connect using an alternate port:

```bash
sftp -P remote_port remote_user@remote_host
```

- Connect using a predefined host (in `~/.ssh/config`):

```bash
sftp host
```

- Transfer remote file to the local system:

```bash
get /path/remote_file
```

- Transfer local file to the remote system:

```bash
put /path/local_file
```

- Transfer remote directory to the local system recursively (works with `put` too):

```bash
get -R /path/remote_directory
```

- Get list of files on local machine:

```bash
lls
```

- Get list of files on remote machine:

```bash
ls
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | sftp: add example (#8142) | 2022-06-21T15:59:48 | [4e0e4d8b6df4](https://github.com/tldr-pages/tldr/commit/4e0e4d8b6df4ddd74da342089856e3800e6a1ac7)
[Juri](mailto:juri.dispan@posteo.net) | meshlabserver, nkf, obs, pax, pdfimages, pinky, pssh, s, sd, sendmail, sftp: add link (#6971) | 2021-10-17T06:23:56 | [977d4212d52c](https://github.com/tldr-pages/tldr/commit/977d4212d52c031de053f549d819b8b0e18ce184)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Shivam Mevawala](mailto:shivmevawala@gmail.com) | sftp: added -R example | 2016-04-01T16:47:57 | [6d98095dc18b](https://github.com/tldr-pages/tldr/commit/6d98095dc18baae853b50532b3fc549fed72542d)
[Shivam Mevawala](mailto:shivmevawala@gmail.com) | sftp: added -R example | 2016-04-01T16:46:33 | [065209473654](https://github.com/tldr-pages/tldr/commit/065209473654b2deaee720ad27b39a824072fe0a)
[slash3b](mailto:slash3b@gmail.com) | sftp: add navigation and transfer examples, incorrect commands were deleted. | 2016-02-07T12:10:32 | [ecd4b1112ba5](https://github.com/tldr-pages/tldr/commit/ecd4b1112ba5d789286db5b454579dbdb847ebd8)
[Peter Tripp](mailto:petertripp@gmail.com) | Rework scp. * No double examples * Replace IP address with hostname place holders. * change word use to avoid upload & download * [...] | 2016-01-16T11:21:23 | [eb973701a19c](https://github.com/tldr-pages/tldr/commit/eb973701a19cc26e1eb3b88723f2800886b4e844)

