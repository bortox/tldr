---
author: ['Kyle', 'bl-ue']
date: 1629747204
title: "GetFileInfo, TLDR Pages"
description: "GetFileInfo, Get information about a file in an HFS+ directory."
categories: "osx"
---
> More information: <https://www.unix.com/man-page/osx/1/GetFileInfo/>.

- Display information about a given file:

```bash
GetFileInfo path/to/filename
```

- Display the date and time a given file was created:

```bash
GetFileInfo -d path/to/filename
```

- Display the date and time a given file was last modified:

```bash
GetFileInfo -m path/to/filename
```

- Display the creator of a given file:

```bash
GetFileInfo -c path/to/filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | GetFileInfo: rename to getfileinfo (#5382) | 2021-03-08T11:41:26 | [f1bbea324d69](https://github.com/tldr-pages/tldr/commit/f1bbea324d69223d9a2ba6d460a00d0ecd229542)

