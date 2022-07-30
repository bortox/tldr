---
author: ['pixel']
date: 1659190122
title: "pkg-config"
description: "pkg-config, Provide the details of installed libraries for compiling applications."
categories: "common"
---
> More information: <https://www.freedesktop.org/wiki/Software/pkg-config/>.

- Get the list of libraries and their dependencies:

```bash
pkg-config --libs library1 library2 ...
```

- Get the list of libraries, their dependencies, and proper cflags for gcc:

```bash
pkg-config --cflags --libs library1 library2 ...
```

- Compile your code with libgtk-3, libwebkit2gtk-4.0 and all their dependencies:

```bash
c++ example.cpp $(pkg-config --cflags --libs gtk+-3.0 webkit2gtk-4.0) -o example
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:pixel@chrissx.de) | pkg-config: move to common (#8267) | 2022-07-30T16:08:42 | [3e124167282b](https://github.com/tldr-pages/tldr/commit/3e124167282bb4890a3f4fb830678c1dfd757671)

