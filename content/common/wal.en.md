---
author: ['Sebastian Alejandro', 'Jorge Medrano']
date: 1653204710
title: "wal"
description: "wal, A tool to create color schemes based on the dominant colors of a wallpaper."
categories: "common"
---
> More information: <https://github.com/dylanaraps/pywal>.

- Preview color scheme:

```bash
wal --preview image.png
```

- Create color scheme:

```bash
wal -i image.png
```

- Create a light color scheme:

```bash
wal -i image.png -l
```

- Skip setting the desktop wallpaper:

```bash
wal -i image.png -n
```

- Skip setting the terminal colors:

```bash
wal -i image.png -s
```

- Restore the previously generated color scheme and wallpaper:

```bash
wal -R
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jorge Medrano](mailto:jamedranoa@unal.edu.co) | wal: fix examples (#8101) pywal expects a path after the -i argument | 2022-05-22T09:31:50 | [2b0026d4fe05](https://github.com/tldr-pages/tldr/commit/2b0026d4fe05535e6bab3240b838326f47078685)
[Sebastian Alejandro](mailto:sebastian1231alejandro@gmail.com) | wal: add page (#3381) | 2019-10-16T07:22:50 | [d1d0f79d975c](https://github.com/tldr-pages/tldr/commit/d1d0f79d975c5340950e90b39ab7baa47b1965aa)

