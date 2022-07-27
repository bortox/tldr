---
author: ['Hojjat']
date: 1589477012
title: "pkg-config, TLDR Pages"
description: "pkg-config, Provide the details of installed libraries for compiling applications."
categories: "linux"
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
[Hojjat](mailto:hojjat.abdollahi@gmail.com) | pkg-config: add page (#4045) | 2020-05-14T19:23:32 | [856f93704e2c](https://github.com/tldr-pages/tldr/commit/856f93704e2c04a59718137498464cae499e635c)

