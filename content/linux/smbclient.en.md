---
author: ['Marco Bonelli', 'Bruno Bigras', 'Jeremy Liberman', 'Emily Grace Seville']
date: 1647882468
title: "smbclient, TLDR Pages"
description: "smbclient, FTP-like client to access SMB/CIFS resources on servers."
categories: "linux"
---
> More information: <https://manned.org/smbclient>.

- Connect to a share (user will be prompted for password; `exit` to quit the session):

```bash
smbclient //server/share
```

- Connect with a different username:

```bash
smbclient //server/share --user username
```

- Connect with a different workgroup:

```bash
smbclient //server/share --workgroup domain --user username
```

- Connect with a username and password:

```bash
smbclient //server/share --user username%password
```

- Download a file from the server:

```bash
smbclient //server/share --directory path/to/directory --command "get file.txt"
```

- Upload a file to the server:

```bash
smbclient //server/share --directory path/to/directory --command "put file.txt"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Bruno Bigras](mailto:bigras.bruno@gmail.com) | smbclient: different 'workgroup/domain' example | 2019-04-08T21:26:22 | [c46e5c1d269b](https://github.com/tldr-pages/tldr/commit/c46e5c1d269b0d246f3bebc970033f312a3af881)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Jeremy Liberman](mailto:mrleebo@msn.com) | smbclient: corrections from peer review | 2018-01-10T17:41:27 | [49a2f7db7625](https://github.com/tldr-pages/tldr/commit/49a2f7db76256bc32abca8bb7ba721ed2bd72f25)
[Jeremy Liberman](mailto:jliberman@strenuus.com) | smbclient: add page | 2018-01-09T21:19:25 | [17d346e22767](https://github.com/tldr-pages/tldr/commit/17d346e2276710b969f79accbc2e3ae028d89efc)

