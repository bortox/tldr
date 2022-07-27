---
author: ['Seth Falco']
date: 1624650187
title: "kscreen-doctor, TLDR Pages"
description: "kscreen-doctor, Change and manipulate the screen setup from the command-line."
categories: "linux"
---
> More information: <https://invent.kde.org/plasma/libkscreen>.

- Show display output information:

```bash
kscreen-doctor --outputs
```

- Set the rotation of a display output with an ID of 1 to the right:

```bash
kscreen-doctor output.1.rotation.right
```

- Set the scale of a display output with an ID of `HDMI-2` to 2 (200%):

```bash
kscreen-doctor output.HDMI-2.scale.2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | kscreen-console, kscreen-doctor: add page (#6078) | 2021-06-25T21:43:07 | [3daf7524fe01](https://github.com/tldr-pages/tldr/commit/3daf7524fe01e8ff1086b0b2e65731d2b0419960)

