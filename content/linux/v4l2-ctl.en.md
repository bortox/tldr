---
author: ['Vinh Quang Tran', 'CleanMachine1']
date: 1651684335
title: "v4l2-ctl"
description: "v4l2-ctl, Control video devices."
categories: "linux"
---
> More information: <https://manned.org/v4l2-ctl>.

- List all video devices:

```bash
v4l2-ctl --list-devices
```

- List supported video formats and resolutions of default video device `/dev/video0`:

```bash
v4l2-ctl --list-formats-ext
```

- List supported video formats and resolutions of a specific video device:

```bash
v4l2-ctl --list-formats-ext --device path/to/video_device
```

- Get all details of a video device:

```bash
v4l2-ctl --all --device path/to/video_device
```

- Capture a JPEG photo with a specific resolution from video device:

```bash
v4l2-ctl --device path/to/video_device --set-fmt-video=width=width,height=height,pixelformat=MJPG --stream-mmap --stream-to=path/to/output.jpg --stream-count=1
```

- Capture a raw video stream from video device:

```bash
v4l2-ctl --device path/to/video_device --set-fmt-video=width=width,height=height,pixelformat=format --stream-mmap --stream-to=path/to/output --stream-count=number_of_frames_to_capture
```

- List all video device's controls and their values:

```bash
v4l2-ctl --list-ctrls --device /path/to/video_device
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | *: fix spelling mistakes (#8072) | 2022-05-04T19:12:15 | [c2a5c8603386](https://github.com/tldr-pages/tldr/commit/c2a5c8603386f1720b996b839802fae1fb60ba8a)
[Vinh Quang Tran](mailto:starcraft6723@hotmail.com) | v4l2-ctl: add page (#7099) | 2021-10-28T05:56:10 | [25e5500195ec](https://github.com/tldr-pages/tldr/commit/25e5500195ec950cbb02e3ee0da8c66ee0f98620)

