---
author: ['Matthew Davidson', 'Andrew Prentice', 'pxgamer']
date: 1559944739
title: "ffprobe, TLDR Pages"
description: "ffprobe, Multimedia stream analyzer."
categories: "common"
---
> More information: <https://ffmpeg.org/ffprobe.html>.

- Display all available stream info for a media file:

```bash
ffprobe -v error -show_entries input.mp4
```

- Display media duration:

```bash
ffprobe -v error -show_entries format=duration -of default=noprint_wrappers=1:nokey=1 input.mp4
```

- Display the frame rate of a video:

```bash
ffprobe -v error -select_streams v:0 -show_entries stream=avg_frame_rate -of default=noprint_wrappers=1:nokey=1 input.mp4
```

- Display the width or height of a video:

```bash
ffprobe -v error -select_streams v:0 -show_entries stream=width|height -of default=noprint_wrappers=1:nokey=1 input.mp4
```

- Display the average bit rate of a video:

```bash
ffprobe -v error -select_streams v:0 -show_entries stream=bit_rate -of default=noprint_wrappers=1:nokey=1 input.mp4
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | ffprobe: add link to homepage | 2019-06-07T23:58:59 | [caf71c1b60d2](https://github.com/tldr-pages/tldr/commit/caf71c1b60d2351ba9fc4f149166454a80c68cc0)
[Matthew Davidson](mailto:matthew@modulolotus.net) | Added bit rate example for ffprobe (#1559) | 2017-10-21T22:56:27 | [9896662914a2](https://github.com/tldr-pages/tldr/commit/9896662914a20959c7ac84b2b1646ebfd56f1f1c)
[Andrew Prentice](mailto:breenger@gmail.com) | ffprobe: add page (#1414) | 2017-06-23T20:04:48 | [58826bfdab2d](https://github.com/tldr-pages/tldr/commit/58826bfdab2dee4e6520b6de614fba2c2d87f762)

