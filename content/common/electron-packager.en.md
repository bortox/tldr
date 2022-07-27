---
author: ['Starkiller645', 'bl-ue']
date: 1621541621
title: "electron-packager, TLDR Pages"
description: "electron-packager, A tool used to build Electron app executables for Windows, Linux and macOS."
categories: "common"
---
> Requires a valid package.json in the application directory.

> More information: <https://github.com/electron/electron-packager>.

- Package an application for the current architecture and platform:

```bash
electron-packager "path/to/app" "app_name"
```

- Package an application for all architectures and platforms:

```bash
electron-packager "path/to/app" "app_name" --all
```

- Package an application for 64-bit Linux:

```bash
electron-packager "path/to/app" "app_name" --platform="linux" --arch="x64"
```

- Package an application for ARM macOS:

```bash
electron-packager "path/to/app" "app_name" --platform="darwin" --arch="arm64"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Starkiller645](mailto:59282118+Starkiller645@users.noreply.github.com) | electron-packager: add page (#4892) | 2020-10-30T22:03:13 | [b83cf195f23f](https://github.com/tldr-pages/tldr/commit/b83cf195f23f2d91d7761a4ee215bd7b952f7f37)

