---
author: ['Sahil Dhiman', 'Balázs Úr', 'pxgamer', 'Morten Fyhn Amundsen', 'Seth Falco', 'Anna']
date: 1629050349
title: "mpv"
description: "mpv, A audio/video player based on MPlayer."
categories: "common"
---
> More information: <https://mpv.io>.

- Play a video or audio file:

```bash
mpv file
```

- Play a video or audio file from a URL:

```bash
mpv 'https://www.youtube.com/watch?v=dQw4w9WgXcQ'
```

- Jump backward/forward 5 seconds:

```bash
LEFT <or> RIGHT
```

- Jump backward/forward 1 minute:

```bash
DOWN <or> UP
```

- Decrease or increase playback speed by 10%:

```bash
[ <or> ]
```

- Play a file at a specified speed (0.01 to 100, default 1):

```bash
mpv --speed speed file
```

- Play a file using a profile defined in the `mpv.conf` file:

```bash
mpv --profile profile_name file
```

- Display the output of webcam or other video input device:

```bash
mpv /dev/video0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | mpv: add play from URL example (#4858) | 2020-10-27T12:06:41 | [d98b3945c11c](https://github.com/tldr-pages/tldr/commit/d98b3945c11ce5d6fd9cd418214e87835c0ce7af)
[Anna](mailto:33095074+annashorthead@users.noreply.github.com) | mpv: add display webcam output example (#4418) | 2020-10-05T15:54:52 | [be791964a9c2](https://github.com/tldr-pages/tldr/commit/be791964a9c27ed2aa5efd597cf24834f559a836)
[pxgamer](mailto:owzie123@gmail.com) | mpv: add link to homepage | 2019-06-04T21:29:40 | [258594f958e8](https://github.com/tldr-pages/tldr/commit/258594f958e8bf6cb2d1787bf0f7e0bdf354d795)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: change Unicode characters to ASCII (#2802) Change Unicode characters to ASCII: - non-breaking spaces (\xc2\xa0) to [...] | 2019-02-25T00:56:24 | [6956cd5348e4](https://github.com/tldr-pages/tldr/commit/6956cd5348e4f87db1586a68ab299e46f7384b63)
[Morten Fyhn Amundsen](mailto:morten.fyhn.amundsen@gmail.com) | mpv: add page (#2314) | 2018-09-09T08:17:49 | [433c1fc7dd2c](https://github.com/tldr-pages/tldr/commit/433c1fc7dd2c74e85e94cfc600a16b54d9c81a2f)

