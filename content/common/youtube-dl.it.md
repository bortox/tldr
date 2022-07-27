---
author: ['Agno94']
date: 1604318864
title: "youtube-dl, TLDR Pages"
description: "youtube-dl, Scarica video da YouTube ed altri siti web."
categories: "common"
---
> Maggiori informazioni: <http://rg3.github.io/youtube-dl/>.

- Scarica un video od una playlist:

```bash
youtube-dl 'https://www.youtube.com/watch?v=oHg5SJYRHA0'
```

- Elenca tutti i formati in cui un video od una playlist sono disponibili:

```bash
youtube-dl --list-formats 'https://www.youtube.com/watch?v=Mwa0_nE9H7A'
```

- Scarica un video od una playlist con la qualità specificata:

```bash
youtube-dl --format "best[height<=480]" 'https://www.youtube.com/watch?v=oHg5SJYRHA0'
```

- Scarica l'audio di un video e lo converte in file MP3:

```bash
youtube-dl -x --audio-format mp3 'url'
```

- Scarica l'audio di migliore qualità e il video di migliore qualità e li unisce:

```bash
youtube-dl -f bestvideo+bestaudio 'url'
```

- Scarica una playlist di video e li salva come file MP4 dai nomi personalizzati:

```bash
youtube-dl --format mp4 -o "%(title)s di %(uploader)s del %(upload_date)s in %(playlist)s.%(ext)s" 'url'
```

- Scarica, assieme al video, i sottotitoli in una lingua specificata:

```bash
youtube-dl --sub-lang it --write-sub 'https://www.youtube.com/watch?v=Mwa0_nE9H7A'
```

- Scarica una playlist, ne estrae l'audio e lo salva in formato mp3:

```bash
youtube-dl -i --extract-audio --audio-format mp3 -o "%(title)s.%(ext)s" 'url_della_playlist'
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Agno94](mailto:agnophi@gmail.com) | ffprobe, flac, id3tag, opusenc, vlc, wget, youtube-dl: add Italian translation (#4869) | 2020-11-02T13:07:44 | [e9eb628533b3](https://github.com/tldr-pages/tldr/commit/e9eb628533b31c09c5951ffa57f4194be88d8f63)

