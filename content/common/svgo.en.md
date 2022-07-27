---
author: ['Waldir Pimenta', 'Jason Axelson', 'Marco Bonelli', 'pxgamer', 'Phil Enzler']
date: 1629223678
title: "svgo, TLDR Pages"
description: "svgo, SVG Optimizer: a Node.js-based tool for optimizing Scalable Vector Graphics files."
categories: "common"
---
> It applies a series of transformation rules (plugins), which can be toggled individually.

> More information: <https://github.com/svg/svgo>.

- Optimize a file using the default plugins (overwrites the original file):

```bash
svgo test.svg
```

- Optimize a file and save the result to another file:

```bash
svgo test.svg -o test.min.svg
```

- Optimize all SVG files within a directory (overwrites the original files):

```bash
svgo -f path/to/directory/with/svg/files
```

- Optimize all SVG files within a directory and save the resulting files to another directory:

```bash
svgo -f path/to/input/directory -o path/to/output/directory
```

- Optimize SVG content passed from another command, and save the result to a file:

```bash
cat test.svg | svgo -i - -o test.min.svg
```

- Optimize a file and print out the result:

```bash
svgo test.svg -o -
```

- Show available plugins:

```bash
svgo --show-plugins
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Phil Enzler](mailto:phil@pushbutton.studio) | svgo: remove deprecated --enable=plugin_name example (#6379) The `--enable` flag was removed in SVGO 2.0. For now, the only way to [...] | 2021-08-17T20:07:58 | [44f8f88d1694](https://github.com/tldr-pages/tldr/commit/44f8f88d1694936b23df52d09220099ec6ef887b)
[Jason Axelson](mailto:axelson@users.noreply.github.com) | Update svgo saving result to a new file (#4367) I'm currently using svgo 1.3.2 which as of right now is the latest released version: [...] | 2020-09-29T12:43:30 | [30c0cd3d4ebc](https://github.com/tldr-pages/tldr/commit/30c0cd3d4ebcbddb5fa33bd92dac09eba8a66162)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | svgo: add link to homepage | 2019-05-14T19:58:59 | [29fcb2dfd0f3](https://github.com/tldr-pages/tldr/commit/29fcb2dfd0f35372a6f6c9ca64b54c5f0e517699)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | svgo: fix spelling of "Node.js" | 2019-01-11T05:06:49 | [6831237aa9a1](https://github.com/tldr-pages/tldr/commit/6831237aa9a1ea48c2faddee278f6f087856b01a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | svgo: add page (#1061) | 2017-04-15T10:52:17 | [f12a12b79230](https://github.com/tldr-pages/tldr/commit/f12a12b7923046e9983224e43b79a27f10307a89)

