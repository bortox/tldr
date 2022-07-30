---
author: ['pixel', 'Seth Falco', 'marchersimon']
date: 1633300301
title: "xcursorgen"
description: "xcursorgen, Create an X cursor file from a collection of PNGs."
categories: "linux"
---
> If `--prefix` is omitted, the image files must be located in the current working directory.

> More information: <https://manned.org/xcursorgen>.

- Create an X cursor file using a config file:

```bash
xcursorgen path/to/config.cursor path/to/output_file
```

- Create an X cursor file using a config file and specify the path to the image files:

```bash
xcursorgen --prefix path/to/image_directory/ path/to/config.cursor path/to/output_file
```

- Create an X cursor file using a config file and write the output to stdout:

```bash
xcursorgen path/to/config.cursor
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | *: removed .1 at the end of manned.org links where it was unnecessary (#6752) | 2021-10-04T00:31:41 | [ceb6654610e9](https://github.com/tldr-pages/tldr/commit/ceb6654610e9bf343485e918edfc5a90691b89d1)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | xcursorgen: add page (#5672) | 2021-04-11T17:00:51 | [3f17e72bf9ef](https://github.com/tldr-pages/tldr/commit/3f17e72bf9efe500796a49474586ab01917874ad)

