---
author: ['Zein Haddad']
date: 1644839080
title: "youtube-dl, TLDR Pages"
description: "youtube-dl, Unduh video dari YouTube dan situs web lain."
categories: "common"
---
> Informasi lebih lanjut: <http://rg3.github.io/youtube-dl/>.

- Mengunduh sebuah video atau daftar putar:

```bash
youtube-dl 'https://www.youtube.com/watch?v=oHg5SJYRHA0'
```

- Tampilkan daftar format yang tersedia untuk video atau daftar putar:

```bash
youtube-dl --list-formats 'https://www.youtube.com/watch?v=Mwa0_nE9H7A'
```

- Mengunduh video atau daftar putar dengan kualitas tertentu:

```bash
youtube-dl --format "best[height<=480]" 'https://www.youtube.com/watch?v=oHg5SJYRHA0'
```

- Mengunduh audio dari video dan ubah menjadi MP3:

```bash
youtube-dl -x --audio-format mp3 'url'
```

- Mengunduh video dan audio dengan kualitas terbaik lalu gabungkan:

```bash
youtube-dl -f bestvideo+bestaudio 'url'
```

- Mengunduh satu atau beberapa video sebagai file MP4 dengan nama tertentu:

```bash
youtube-dl --format mp4 -o "%(playlist_index)s-%(title)s oleh %(uploader)s pada %(upload_date)s di dalam %(playlist)s.%(ext)s" 'url'
```

- Mengunduh video bersama dengan subtitle bahasa tertentu:

```bash
youtube-dl --sub-lang en --write-sub 'https://www.youtube.com/watch?v=Mwa0_nE9H7A'
```

- Mengunduh daftar putar dan ekstrak MP3 darinya:

```bash
youtube-dl -f "bestaudio" --continue --no-overwrites --ignore-errors --extract-audio --audio-format mp3 -o "%(title)s.%(ext)s" url_to_playlist
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Zein Haddad](mailto:zeinhaddad02@gmail.com) | dnf, youtube-dl: add Indonesian translation (#7766) | 2022-02-14T12:44:40 | [2db31619792a](https://github.com/tldr-pages/tldr/commit/2db31619792ac45f8bd79a368b5e10dc51690702)

