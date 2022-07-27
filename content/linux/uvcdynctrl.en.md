---
author: ['Shanoop Padmanabhan', 'fejx', 'bl-ue', 'Emily Grace Seville']
date: 1647882468
title: "uvcdynctrl, TLDR Pages"
description: "uvcdynctrl, A libwebcam command-line tool to manage dynamic controls in uvcvideo."
categories: "linux"
---
> More information: <https://manned.org/uvcdynctrl>.

- List all available cameras:

```bash
uvcdynctrl -l
```

- Specify the device to use (defaults to `video0`):

```bash
uvcdynctrl -d device_name
```

- List available controls:

```bash
uvcdynctrl -c
```

- Set a new control value (for negative values, add -- before {{-value}}):

```bash
uvcdynctrl -s control_name value
```

- Get the current control value:

```bash
uvcdynctrl -g control_name
```

- Save the state of the current controls to a file:

```bash
uvcdynctrl -W filename
```

- Load the state of the controls from a file:

```bash
uvcdynctrl -L filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[fejx](mailto:florian.jhn@gmail.com) | Change all occurrences of file_name to filename (#4059) | 2020-05-22T14:31:24 | [4e1662b729ba](https://github.com/tldr-pages/tldr/commit/4e1662b729ba2bc23f7c12f606d41a86a613f8ea)
[Shanoop Padmanabhan](mailto:shanoop_234@hotmail.com) | uvcdynctrl : add page (#3408) | 2019-10-19T17:48:30 | [ecebc8202045](https://github.com/tldr-pages/tldr/commit/ecebc820204511b818cf6068705bc520dd6754e9)

