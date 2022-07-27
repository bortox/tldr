---
author: ['Yuriy Bash', 'Kyle', 'Viktor Szakats']
date: 1629747204
title: "chflags, TLDR Pages"
description: "chflags, Change file or directory flags."
categories: "osx"
---
> More information: <https://ss64.com/osx/chflags.html>.

- Set the `hidden` flag for a file:

```bash
chflags hidden path/to/file
```

- Unset the `hidden` flag for a file:

```bash
chflags nohidden path/to/file
```

- Recursively set the `uchg` flag for a directory:

```bash
chflags -R uchg path/to/directory
```

- Recursively unset the `uchg` flag for a directory:

```bash
chflags -R nouchg path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Viktor Szakats](mailto:vszakats@users.noreply.github.com) | chflags: add missing 'no' to clear hidden flag (#3235) | 2019-08-14T10:13:55 | [dec9fb400bb7](https://github.com/tldr-pages/tldr/commit/dec9fb400bb7bac4778a752567f58be4815eb668)
[Yuriy Bash](mailto:yuriybash@users.noreply.github.com) | chflags: add page (#2682) | 2019-01-07T04:58:55 | [e26abe5a75fc](https://github.com/tldr-pages/tldr/commit/e26abe5a75fc4d438b0da3b99e3766b6ccabab38)

