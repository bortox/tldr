---
author: ['Axel Navarro']
date: 1632451356
title: "gh screensaver, TLDR Pages"
description: "gh screensaver, Extension for GitHub CLI that runs animated terminal screensavers."
categories: "common"
---
> See also: `gh extension`.

> More information: <https://github.com/vilmibm/gh-screensaver>.

- Run a random screensaver:

```bash
gh screensaver
```

- Run a specific screensaver:

```bash
gh screensaver --saver fireworks|marquee|pipes|pollock|starfield
```

- Run the "marquee" screensaver with a specific text and font:

```bash
gh screensaver --saver marquee -- --message="message" --font=font_name
```

- Run the "starfield" screensaver with a specific density and speed:

```bash
gh screensaver --saver starfield -- --density 500 --speed 10
```

- List available screensavers:

```bash
gh screensaver --list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-screensaver: add page (#6578) | 2021-09-24T04:42:36 | [68125f7c60ff](https://github.com/tldr-pages/tldr/commit/68125f7c60ff915fb36229fbe7515e4eb8e7f393)

