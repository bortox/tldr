---
author: ['lbonanomi', 'Sadeed']
date: 1634674843
title: "ulimit, TLDR Pages"
description: "ulimit, Get and set user limits."
categories: "common"
---
> More information: <https://manned.org/ulimit>.

- Get the properties of all the user limits:

```bash
ulimit -a
```

- Get hard limit for the number of simultaneously opened files:

```bash
ulimit -H -n
```

- Get soft limit for the number of simultaneously opened files:

```bash
ulimit -S -n
```

- Set max per-user process limit:

```bash
ulimit -u 30
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | ufraw-batch, ulimit, umask, umount, unalias, unar, unclutter, unrar, unzip: add link (#7092) | 2021-10-19T22:20:43 | [02441ef2ba43](https://github.com/tldr-pages/tldr/commit/02441ef2ba43268b294d2148ff1c7aa439a2d9ec)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | ulimit: move to common/ | 2019-05-23T18:15:31 | [65a5f271d4f4](https://github.com/tldr-pages/tldr/commit/65a5f271d4f412c508f0f261f47e3d6da50d5249)

