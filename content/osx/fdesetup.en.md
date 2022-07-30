---
author: ['Kyle', 'Adnan Emil Abdulai', 'Emily Grace Seville']
date: 1644837703
title: "fdesetup"
description: "fdesetup, Set and retrieve FileVault related information."
categories: "osx"
---
> More information: <https://www.unix.com/man-page/mojave/8/fdesetup/>.

- List current FileVault enabled users:

```bash
sudo fdesetup list
```

- Get current FileVault status:

```bash
fdesetup status
```

- Add FileVault enabled user:

```bash
sudo fdesetup add -usertoadd user1
```

- Enable FileVault:

```bash
sudo fdesetup enable
```

- Disable FileVault:

```bash
sudo fdesetup disable
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Adnan Emil Abdulai](mailto:emilshouse@gmail.com) | fdesetup: add page (#4011) | 2020-04-30T20:20:25 | [30a10e44f6a9](https://github.com/tldr-pages/tldr/commit/30a10e44f6a9b11be1439b01598ac72ecb4c95f9)

