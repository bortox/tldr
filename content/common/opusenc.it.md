---
author: ['Agno94']
date: 1604318864
title: "opusenc, TLDR Pages"
description: "opusenc, Converte audio WAV o FLAC in Opus."
categories: "common"
---
> Maggiori informazioni: <https://opus-codec.org/docs/opus-tools/opusenc.html>.

- Converte un file WAV in un file Opus usando le opzioni predefinite:

```bash
opusenc percorso/al/file_originale.wav percorso/al/file_convertito.opus
```

- Converte un audio stereo alla massima qualità possibile:

```bash
opusenc --bitrate 512 percorso/al/file_originale.wav percorso/al/file_convertito.opus
```

- Converte un audio con canali surround 5.1 alla massima qualità possibile:

```bash
opusenc --bitrate 1536 percorso/al/file_originale.flac percorso/al/file_convertito.opus
```

- Converte l'audio di una voce alla minima qualità possibile:

```bash
opusenc percorso/al/file_originale.wav --downmix-mono --bitrate 6 percorso/al/file_convertito.opus
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Agno94](mailto:agnophi@gmail.com) | ffprobe, flac, id3tag, opusenc, vlc, wget, youtube-dl: add Italian translation (#4869) | 2020-11-02T13:07:44 | [e9eb628533b3](https://github.com/tldr-pages/tldr/commit/e9eb628533b31c09c5951ffa57f4194be88d8f63)

