---
author: ['aaaawwWWWwwwwWWW']
date: 1606402492
title: "veracrypt"
description: "veracrypt, Free and open source disk encryption software."
categories: "linux"
---
> More information: <https://www.veracrypt.fr/code/VeraCrypt/plain/doc/html/Documentation.html>.

- Create a new volume through a text user interface and use `/dev/urandom` as a source of random data:

```bash
veracrypt --text --create --random-source=/dev/urandom
```

- Decrypt a volume interactively through a text user interface and mount it to a directory:

```bash
veracrypt --text path/to/volume path/to/mount_point
```

- Decrypt a partition using a keyfile and mount it to a directory:

```bash
veracrypt --keyfiles=path/to/keyfile /dev/sdXN path/to/mount_point
```

- Dismount a volume on the directory it is mounted to:

```bash
veracrypt --dismount path/to/mounted_point
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[aaaawwWWWwwwwWWW](mailto:73749744+aaaawwWWWwwwwWWW@users.noreply.github.com) | veracrypt: add page (#4967) | 2020-11-26T15:54:52 | [f85df16180c2](https://github.com/tldr-pages/tldr/commit/f85df16180c2c8b04888ba72e9fa0b66322de262)

