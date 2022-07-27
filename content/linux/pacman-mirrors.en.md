---
author: ['marchersimon']
date: 1614533027
title: "pacman-mirrors, TLDR Pages"
description: "pacman-mirrors, Generate a pacman mirrorlist for Manjaro Linux."
categories: "linux"
---
> Every run of pacman-mirrors requires you to synchronize your database and update your system using `sudo pacman -Syyu`.

> More information: <https://wiki.manjaro.org/index.php?title=Pacman-mirrors>.

- Generate a mirrorlist using the default settings:

```bash
sudo pacman-mirrors --fasttrack
```

- Get the status of the current mirrors:

```bash
pacman-mirrors --status
```

- Display the current branch:

```bash
pacman-mirrors --get-branch
```

- Switch to a different branch:

```bash
sudo pacman-mirrors --api --set-branch stable|unstable|testing
```

- Generate a mirrorlist, only using mirrors in your country:

```bash
sudo pacman-mirrors --geoip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman-mirrors: add page (#5315) | 2021-02-28T18:23:47 | [20e56e6c92bb](https://github.com/tldr-pages/tldr/commit/20e56e6c92bbbb433e2135f2b7901f21f75b1ed8)

