---
author: ['Waldir Pimenta', 'Jon LaBelle', 'Kyle', 'Daniel Senff']
date: 1629747204
title: "id3tag, TLDR Pages"
description: "id3tag, Tool for reading, writing, and manipulating ID3v1 and ID3v2 tags of MP3 files."
categories: "common"
---
> More information: <https://manned.org/id3tag>.

- Set artist and title tag of an MP3 file:

```bash
id3tag --artist=artist --title=title path/to/file.mp3
```

- Set album title of all MP3 files in the current directory:

```bash
id3tag --album=album *.mp3
```

- Get more help:

```bash
id3tag --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | id3tag: minor tweaks (#1347) | 2017-04-22T15:37:16 | [777073fcb80d](https://github.com/tldr-pages/tldr/commit/777073fcb80da43117c7bce9e2bd2f956b2ca58c)
[Jon LaBelle](mailto:contact@jonlabelle.com) | id3tag: Trim trailing whitespace in first example | 2017-03-26T20:16:23 | [7549db275b17](https://github.com/tldr-pages/tldr/commit/7549db275b1707e656fca6991edf3b16594f27b6)
[Daniel Senff](mailto:mail@danielsenff.de) | id3tag.md: add page (#1280) | 2017-03-25T07:36:30 | [3276058ed969](https://github.com/tldr-pages/tldr/commit/3276058ed96968e3d823ac6282fad9ae19aeb1e3)

