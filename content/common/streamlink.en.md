---
author: ['Quentin']
date: 1597016129
title: "streamlink"
description: "streamlink, Extracts streams from various services and pipes them into a video player of choice."
categories: "common"
---
> More information: <https://streamlink.github.io>.

- Attempt to extract streams from the URL specified, and if it's successful, print out a list of available streams to choose from:

```bash
streamlink example.com/stream
```

- Open a stream with the specified quality:

```bash
streamlink example.com/stream 720p60
```

- Select the highest or lowest available quality:

```bash
streamlink example.com/stream best|worst
```

- Specify which player to use to feed stream data to (VLC is used by default if found):

```bash
streamlink --player=mpv example.com/stream best
```

- Specify the amount of time to skip from the beginning of the stream. For live streams, this is a negative offset from the end of the stream (rewind):

```bash
streamlink --hls-start-offset [HH:]MM:SS example.com/stream best
```

- Skip to the beginning of a live stream, or as far back as possible:

```bash
streamlink --hls-live-restart example.com/stream best
```

- Write stream data to a file instead of playing it:

```bash
streamlink --output path/to/file.ts example.com/stream best
```

- Open the stream in the player, while at the same time writing it to a file:

```bash
streamlink --record path/to/file.ts example.com/stream best
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Quentin](mailto:quentin.bettoum@mailo.com) | streamlink: add page (#4242) * streamlink: add page * Edit with suggestions from PR | 2020-08-10T01:35:29 | [cf27351f6e60](https://github.com/tldr-pages/tldr/commit/cf27351f6e60f9b6f4d0d705fb3e3b8dbf5364d9)

