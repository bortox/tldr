---
author: ['Bruno Heridet']
date: 1571991139
title: "pastel"
description: "pastel, Generate, analyze, convert and manipulate colors."
categories: "common"
---
> More information: <https://github.com/sharkdp/pastel>.

- Convert colors from one format to another. Here from RGB to HSL:

```bash
pastel format hsl ff8000
```

- Show and analyze colors on the terminal:

```bash
pastel color "rgb(255,50,127)"
```

- Pick a color from somewhere on the screen:

```bash
pastel pick
```

- Generate a set of N visually distinct colors:

```bash
pastel distinct 8
```

- Get a list of all X11 / CSS color names:

```bash
pastel list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bruno Heridet](mailto:delapouite@gmail.com) | pastel: add page (#3443) | 2019-10-25T10:12:19 | [3d9b1d58b3d5](https://github.com/tldr-pages/tldr/commit/3d9b1d58b3d5a4deb7bb0170d7250b1933ff38de)

