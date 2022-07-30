---
author: ['Howard Yun']
date: 1635335490
title: "wsl-open"
description: "wsl-open, Open a file or URL from within Windows Subsystem for Linux in the user's default Windows GUI application."
categories: "windows"
---
> More information: <https://gitlab.com/4U6U57/wsl-open>.

- Open the current directory in Windows Explorer:

```bash
wsl-open .
```

- Open a URL in the user's default web browser in Windows:

```bash
wsl-open https://example.com
```

- Open a specific file in the user's default application in Windows:

```bash
wsl-open path/to/file
```

- Set `wsl-open` as the shell's web browser (open links with `wsl-open`):

```bash
wsl-open -w
```

- Display help:

```bash
wsl-open -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Howard Yun](mailto:Haoy2001@gmail.com) | wsl-open: add page (#7007) | 2021-10-27T13:51:30 | [aab0a794acd4](https://github.com/tldr-pages/tldr/commit/aab0a794acd4ca37d1e6f6d2b3d9be2c2dedd141)

