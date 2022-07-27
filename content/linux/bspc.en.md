---
author: ['Raffaele Mignone']
date: 1635599624
title: "bspc, TLDR Pages"
description: "bspc, A tool to control `bspwm`."
categories: "linux"
---
> More information: <https://github.com/baskerville/bspwm>.

- Define two virtual desktop:

```bash
bspc monitor --reset-desktops 1 2
```

- Focus the given desktop:

```bash
bspc desktop --focus number
```

- Close the windows rooted at the selected node:

```bash
bspc node --close
```

- Send the selected node to the given desktop:

```bash
bspc node --to-desktop number
```

- Toggle full screen mode for the selected node:

```bash
bspc node --state ~fullscreen
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Raffaele Mignone](mailto:github@norangeb.it) | bspc, bspwm: add page (#7215) | 2021-10-30T15:13:44 | [1611c5f0a2d6](https://github.com/tldr-pages/tldr/commit/1611c5f0a2d694691677780c359ff41a6b2ef2a6)

