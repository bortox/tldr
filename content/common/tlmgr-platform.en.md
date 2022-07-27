---
author: ['marchersimon']
date: 1632282880
title: "tldr platform, TLDR Pages"
description: "tldr platform, Manage TeX Live platforms."
categories: "common"
---
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- List all available platforms in the package repository:

```bash
tlmgr platform list
```

- Add the executables for a specific platform:

```bash
sudo tlmgr platform add platform
```

- Remove the executables for a specific platform:

```bash
sudo tlmgr platform remove platform
```

- Auto-detect and switch to the current platform:

```bash
sudo tlmgr platform set auto
```

- Switch to a specific platform:

```bash
sudo tlmgr platform set platform
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-platform, tlmgr-arch: add page (#6561) | 2021-09-22T05:54:40 | [555faac0d2f5](https://github.com/tldr-pages/tldr/commit/555faac0d2f5943e8f0969f980b941ddb1089b11)

