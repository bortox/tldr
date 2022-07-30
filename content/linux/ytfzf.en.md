---
author: ['kyteinsky']
date: 1638110105
title: "ytfzf"
description: "ytfzf, A POSIX script that helps you find and download videos and music."
categories: "linux"
---
> More information: <https://github.com/pystardust/ytfzf>.

- Search for videos on YouTube with thumbnail previews:

```bash
ytfzf --show-thumbnails search_pattern
```

- Play only the audio of the first item in a loop:

```bash
ytfzf --audio-only --auto-select --loop search_pattern
```

- Download a video from the history:

```bash
ytfzf --download --choose-from-history
```

- Play all the music found in a search:

```bash
ytfzf --audio-only --select-all search_pattern
```

- See the trending videos in an external menu:

```bash
ytfzf --trending --ext-menu search_pattern
```

- Search on PeerTube instead of YouTube:

```bash
ytfzf --peertube search_pattern
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[kyteinsky](mailto:kyteinsky@gmail.com) | ytfzf: add page (#7458) | 2021-11-28T15:35:05 | [d3e2dc900c4a](https://github.com/tldr-pages/tldr/commit/d3e2dc900c4a78ff7aa7bc0db236f219fa2d38e0)

