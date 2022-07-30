---
author: ['Guido Lena Cota', 'Kyle']
date: 1629747204
title: "asr"
description: "asr, Restore (copy) a disk image onto a volume."
categories: "osx"
---
> The command name stands for Apple Software Restore.

> More information: <https://www.unix.com/man-page/osx/8/asr/>.

- Restore a disk image to a target volume:

```bash
sudo asr restore --source image_name.dmg --target path/to/volume
```

- Erase the target volume before restoring:

```bash
sudo asr restore --source image_name.dmg --target path/to/volume --erase
```

- Skip verification after restoring:

```bash
sudo asr restore --source image_name.dmg --target path/to/volume --noverify
```

- Clone volumes without the use of an intermediate disk image:

```bash
sudo asr restore --source path/to/volume --target path/to/cloned_volume
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | asr: add page (#2464) | 2018-10-21T22:44:14 | [cb3d02239cc1](https://github.com/tldr-pages/tldr/commit/cb3d02239cc169b687e570be44e7f131bc6a3ff1)

