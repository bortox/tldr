---
author: ['Owen Voke']
date: 1600794415
title: "takeown, TLDR Pages"
description: "takeown, Take ownership of a file or directory."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/takeown>.

- Take ownership of the specified file:

```bash
takeown /f path/to/file
```

- Take ownership of the specified directory:

```bash
takeown /d path/to/directory
```

- Take ownership of the specified directory and all subdirectories:

```bash
takeown /r /d path/to/directory
```

- Change ownership to the Administrator group instead of the current user:

```bash
takeown /a /f path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Owen Voke](mailto:owzie123@gmail.com) | takeown: add page (#3252) | 2019-08-23T18:56:41 | [69b65ed3605f](https://github.com/tldr-pages/tldr/commit/69b65ed3605f7522bda0550a41c1ba78f4deedb7)

