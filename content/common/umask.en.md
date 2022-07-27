---
author: ['lbonanomi', 'Sadeed']
date: 1634674843
title: "umask, TLDR Pages"
description: "umask, Manage the read/write/execute permissions that are masked out (i.e. restricted) for newly created files by the user."
categories: "common"
---
> More information: <https://manned.org/umask>.

- Display the current mask in octal notation:

```bash
umask
```

- Display the current mask in symbolic (human-readable) mode:

```bash
umask -S
```

- Change the mask symbolically to allow read permission for all users (the rest of the mask bits are unchanged):

```bash
umask a+r
```

- Set the mask (using octal) to restrict no permissions for the file's owner, and restrict all permissions for everyone else:

```bash
umask 077
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | ufraw-batch, ulimit, umask, umount, unalias, unar, unclutter, unrar, unzip: add link (#7092) | 2021-10-19T22:20:43 | [02441ef2ba43](https://github.com/tldr-pages/tldr/commit/02441ef2ba43268b294d2148ff1c7aa439a2d9ec)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | umask: move to common/ | 2019-05-23T18:15:31 | [de4e856b97e5](https://github.com/tldr-pages/tldr/commit/de4e856b97e5196c9df8cc946e985aca08e39fa2)

