---
author: ['Waldir Pimenta', 'Sadeed', 'marchersimon']
date: 1625253777
title: "deemix, TLDR Pages"
description: "deemix, A barebone deezer downloader library built from the ashes of Deezloader Remix."
categories: "common"
---
> It can be used as a standalone CLI app or implemented in a UI using the API.

> More information: <https://deemix.app>.

- Download a track or playlist:

```bash
deemix https://www.deezer.com/us/track/00000000
```

- Download track / playlist at a specific bitrate:

```bash
deemix --bitrate FLAC|MP3 url
```

- Download to a specific path:

```bash
deemix --bitrate bitrate --path path url
```

- Create a portable deemix config in the current directory:

```bash
deemix --portable --bitrate bitrate --path path url
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Fix syntax of "More information" links (#5050) | 2020-12-29T12:46:54 | [5430739f1dc4](https://github.com/tldr-pages/tldr/commit/5430739f1dc4d29b85b838e594550ba6c133001f)
[Sadeed](mailto:sadeeedw@gmail.com) | deemix: add page (#4381) | 2020-10-05T17:10:50 | [301c70735b03](https://github.com/tldr-pages/tldr/commit/301c70735b0377b9d1ba1ddc44184ce445a761aa)

