---
author: ['Managor']
date: 1635464975
title: "ffplay, TLDR Pages"
description: "ffplay, A simple and portable media player using the FFmpeg libraries and the SDL library."
categories: "common"
---
> More information: <https://ffmpeg.org/ffplay-all.html>.

- Play a media file:

```bash
ffplay path/to/file
```

- Play a video and show motion vectors in real time:

```bash
ffplay -flags2 +export_mvs -vf codecview=mv=pf+bf+bb path/to/file
```

- Show only video keyframes:

```bash
ffplay -vf select="eq(pict_type\,PICT_TYPE_I)" path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Managor](mailto:42655600+Managor@users.noreply.github.com) | ffplay: add page (#7270) * ffplay: add page * backtick * Update pages/common/ffplay.md Co-authored-by: Muhammad Falak R Wani [...] | 2021-10-29T01:49:35 | [39c87b035830](https://github.com/tldr-pages/tldr/commit/39c87b0358306370b022b7fbf967233f52ffc496)

