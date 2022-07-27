---
author: ['MDecker-MobileComputing']
date: 1636301770
title: "mp3info, TLDR Pages"
description: "mp3info, Viewer/editor for ID3v1 (but not ID3v2) tags of MP3 files."
categories: "common"
---
> More information: <http://www.ibiblio.org/mp3info>.

- Show all ID3v1 tags of a specific MP3 file:

```bash
mp3info path/to/file.mp3
```

- Edit ID3v1 tags interactively:

```bash
mp3info -i path/to/file.mp3
```

- Set values for ID3v1 tags in a specific MP3 file:

```bash
mp3info -a "artist_name" -t "song_title" -l "album_title" -y year -c "comment_text" path/to/file.mp3
```

- Set the number of the track in the album for a specific MP3 file:

```bash
mp3info -n track_number path/to/file.mp3
```

- Print a list of valid genres and their numeric codes:

```bash
mp3info -G
```

- Set the music genre for a specific MP3 file:

```bash
mp3info -g genre_number path/to/file.mp3
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[MDecker-MobileComputing](mailto:mide_42b@yahoo.de) | mp3info: add page (#7235) | 2021-11-07T17:16:10 | [90be54b197ff](https://github.com/tldr-pages/tldr/commit/90be54b197ff2415c93d86bea1ed3cc67191c0ce)

