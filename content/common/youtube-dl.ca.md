---
author: ['Seifer23']
date: 1648937645
title: "youtube-dl"
description: "youtube-dl, Descarrega videos de YouTube i altres pàgines web."
categories: "common"
---
> Més informació: <http://rg3.github.io/youtube-dl/>.

- Descarrega un vídeo o playlist:

```bash
youtube-dl 'https://www.youtube.com/watch?v=oHg5SJYRHA0'
```

- Llista tots els formats en el que es troba disponible un vídeo o playlist:

```bash
youtube-dl --list-formats 'https://www.youtube.com/watch?v=Mwa0_nE9H7A'
```

- Descarrega un vídeo o playlist en una qualitat específica:

```bash
youtube-dl --format "best[height<=480]" 'https://www.youtube.com/watch?v=oHg5SJYRHA0'
```

- Descarrega l'àudio d'un vídeo i converteix-lo a MP3:

```bash
youtube-dl -x --audio-format mp3 'url'
```

- Descarrega l'àudio i el vídeo de major qualitat i fusiona'ls:

```bash
youtube-dl -f bestvideo+bestaudio 'url'
```

- Descarrega vídeo(s) com a fitxers MP4 amb un nom específic:

```bash
youtube-dl --format mp4 -o "%(playlist_index)s-%(title)s by %(uploader)s on %(upload_date)s in %(playlist)s.%(ext)s" 'url'
```

- Descarrega els subtítols d'un llenguatge en concret amb el vídeo:

```bash
youtube-dl --sub-lang en --write-sub 'https://www.youtube.com/watch?v=Mwa0_nE9H7A'
```

- Descarrega una playlist i extreu-ne els MP3s:

```bash
youtube-dl -f "bestaudio" --continue --no-overwrites --ignore-errors --extract-audio --audio-format mp3 -o "%(title)s.%(ext)s" url_to_playlist
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | 7z, cmatrix, ls, youtube-dl: add Catalan translation (#7946) | 2022-04-03T00:14:05 | [f3f11bd53901](https://github.com/tldr-pages/tldr/commit/f3f11bd5390198c2c709bcbc4913f65ad28e702d)

