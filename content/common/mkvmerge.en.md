---
author: ['Julien Tremblay McLellan - Library & Information Science']
date: 1620766820
title: "mkvmerge"
description: "mkvmerge, Merge and extract multimedia streams."
categories: "common"
---
> More information: <https://mkvtoolnix.download/doc/mkvmerge.html>.

- Display information about a Matroska file:

```bash
mkvmerge --identify path/to/file.mkv
```

- Extract the audio from track 1 of a specific file:

```bash
mkvextract tracks path/to/file.mkv 1:path/to/output.webm
```

- Extract the subtitle from track 3 of a specific file:

```bash
mkvextract tracks path/to/file.mkv 3:path/to/subs.srt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Julien Tremblay McLellan - Library & Information Science](mailto:jtremc@gmail.com) | mkvmerge: add page (#5943) | 2021-05-11T23:00:20 | [145ae4905e45](https://github.com/tldr-pages/tldr/commit/145ae4905e45316b16f900449bf87c425e832607)

