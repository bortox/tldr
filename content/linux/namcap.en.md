---
author: ['CleanMachine1', 'Saikat Sengupta']
date: 1640471897
title: "namcap, TLDR Pages"
description: "namcap, Check binary packages and source `PKGBUILD`s for common packaging mistakes."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/namcap.1>.

- Check a specific `PKGBUILD` file:

```bash
namcap path/to/pkgbuild
```

- Check a specific package file:

```bash
namcap path/to/package.pkg.tar.zst
```

- Check a file, printing extra [i]nformational messages:

```bash
namcap -i path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | namcap: fix error (#7576) | 2021-12-25T23:38:17 | [60333f871c5a](https://github.com/tldr-pages/tldr/commit/60333f871c5a93f34cd6671b2166a6802f7e0cab)
[Saikat Sengupta](mailto:41847480+s4ik4t@users.noreply.github.com) | namcap: add page (#6722) | 2021-10-06T23:33:17 | [5c431cf3e723](https://github.com/tldr-pages/tldr/commit/5c431cf3e7239c35022a62123cd5a7c37b5e75ad)

