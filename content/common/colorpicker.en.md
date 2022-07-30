---
author: ['marchersimon']
date: 1623436578
title: "colorpicker"
description: "colorpicker, A minimalist X11 colorpicker."
categories: "common"
---
> Any mouse gesture except left click will exit the program.

> More information: <https://github.com/ym1234/colorpicker>.

- Launch colorpicker and print the hexadecimal and RGB value of each clicked pixel to stdout:

```bash
colorpicker
```

- Only print the color of one clicked pixel and then exit:

```bash
colorpicker --one-shot
```

- Print the color of each clicked pixel and quit when a key is pressed:

```bash
colorpicker --quit-on-keypress
```

- Only print the RGB value:

```bash
colorpicker --rgb
```

- Only print the hexadecimal value:

```bash
colorpicker --hex
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | colorpicker: add page (#6098) | 2021-06-11T20:36:18 | [aebd17a6cb59](https://github.com/tldr-pages/tldr/commit/aebd17a6cb5959d076a83c278b122b48a1e3b40d)

