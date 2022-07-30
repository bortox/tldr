---
author: ['nik']
date: 1645403588
title: "yt-dlp"
description: "yt-dlp, A youtube-dl fork with additional features and fixes."
categories: "common"
---
> Download videos from YouTube and other websites.

> More information: <https://github.com/yt-dlp/yt-dlp>.

- Download a video or playlist (with the default options from command below):

```bash
yt-dlp "https://www.youtube.com/watch?v=oHg5SJYRHA0"
```

- Download a video with a defined format. In this case merging the best video format with the best audio format (Default):

```bash
yt-dlp --format "bv*+ba/b" "https://www.youtube.com/watch?v=oHg5SJYRHA0"
```

- Extract audio from videos (required ffmpeg or ffprobe):

```bash
yt-dlp --extract-audio "https://www.youtube.com/watch?v=oHg5SJYRHA0"
```

- Specify audio format of extracted audio (best(default), aac, flac, mp3, m4a, opus, vorbis, wav, alac):

```bash
yt-dlp --extract-audio --audio-format mp3 "https://www.youtube.com/watch?v=oHg5SJYRHA0"
```

- Specify audio quality of extracted audio (between 0 (best) and 10 (worst), default = 5):

```bash
yt-dlp --extract-audio --audio-format mp3 --audio-quality 0 "https://www.youtube.com/watch?v=oHg5SJYRHA0"
```

- Download all playlists of YouTube channel/user keeping each playlist in separate directory:

```bash
yt-dlp -o "%(uploader)s/%(playlist)s/%(playlist_index)s - %(title)s.%(ext)s" "https://www.youtube.com/user/TheLinuxFoundation/playlists"
```

- Download Udemy course keeping each chapter in separate directory under MyVideos directory in your home:

```bash
yt-dlp -u user -p password -P "~/MyVideos" -o "%(playlist)s/%(chapter_number)s - %(chapter)s/%(title)s.%(ext)s" "https://www.udemy.com/java-tutorial"
```

- Download entire series season keeping each series and each season in separate directory under C:/MyVideos:

```bash
yt-dlp -P "C:/MyVideos" -o "%(series)s/%(season_number)s - %(season)s/%(episode_number)s - %(episode)s.%(ext)s" "https://videomore.ru/kino_v_detalayah/5_sezon/367617"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[nik](mailto:niklas.mertens@ipa.fraunhofer.de) | yt-dlp: add page (#7628) * add yt-dlp page * fix format * remove file * fix unprecise explanation * Delete .gitpod.yml | 2022-02-21T01:33:08 | [ac627da6685a](https://github.com/tldr-pages/tldr/commit/ac627da6685a5aed1c78ab119fac178a35d9a236)

