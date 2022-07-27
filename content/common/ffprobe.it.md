---
author: ['Agno94']
date: 1604318864
title: "ffprobe, TLDR Pages"
description: "ffprobe, Analizzatore di flussi multimediali."
categories: "common"
---
> Maggiori informazioni: <https://ffmpeg.org/ffprobe.html>.

- Visualizza tutte le informazioni disponibili sui flussi di un file multimediale (audio, video, immagini, etc):

```bash
ffprobe -v error -show_entries file.mp4
```

- Visualizza la durata del contenuto:

```bash
ffprobe -v error -show_entries format=duration -of default=noprint_wrappers=1:nokey=1 file.mp4
```

- Visualizza la frequenza dei fotogrammi di un video:

```bash
ffprobe -v error -select_streams v:0 -show_entries stream=avg_frame_rate -of default=noprint_wrappers=1:nokey=1 video.mp4
```

- Visualizza la larghezza o l'altezza di un video:

```bash
ffprobe -v error -select_streams v:0 -show_entries stream=width|height -of default=noprint_wrappers=1:nokey=1 video.mp4
```

- Visualizza il bit-rate medio di un video:

```bash
ffprobe -v error -select_streams v:0 -show_entries stream=bit_rate -of default=noprint_wrappers=1:nokey=1 video.mp4
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Agno94](mailto:agnophi@gmail.com) | ffprobe, flac, id3tag, opusenc, vlc, wget, youtube-dl: add Italian translation (#4869) | 2020-11-02T13:07:44 | [e9eb628533b3](https://github.com/tldr-pages/tldr/commit/e9eb628533b31c09c5951ffa57f4194be88d8f63)

