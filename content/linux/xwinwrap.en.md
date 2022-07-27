---
author: ['Henrique Tsuyoshi Yara']
date: 1633985073
title: "xwinwrap, TLDR Pages"
description: "xwinwrap, Run a player or a program as desktop background."
categories: "linux"
---
> More information: <https://github.com/ujjwal96/xwinwrap>.

- Run a video using mpv:

```bash
xwinwrap -b -nf -ov -- mpv -wid wid --loop --no-audio --no-resume-playback --panscan=1.0 path/to/video.mp4
```

- Run a video in fullscreen using mpv:

```bash
xwinwrap -b -nf -fs -ov -- mpv -wid wid --loop --no-audio --no-resume-playback --panscan=1.0 path/to/video.mp4
```

- Run a video using mpv with 80% opacity:

```bash
xwinwrap -b -nf -ov -o 0.8 --- mpv -wid wid --loop --no-audio --no-resume-playback --panscan=1.0 path/to/video.mp4
```

- Run a video using mpv in a second monitor 1600x900 with 1920 offset on X-axis:

```bash
xwinwrap -g 1600x900+1920 -b -nf -ov -- mpv -wid wid --loop --no-audio --no-resume-playback --panscan=1.0 path/to/video.mkv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Henrique Tsuyoshi Yara](mailto:henri.tsuyoshi@hotmail.com) | xwinwrap: add page (#6852) | 2021-10-11T22:44:33 | [8d8f37156128](https://github.com/tldr-pages/tldr/commit/8d8f37156128b115a41d585259fee1be1d70a9bb)

