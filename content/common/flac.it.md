---
author: ['Agno94']
date: 1604318864
title: "flac, TLDR Pages"
description: "flac, Codifica, decodifica e controlla file flac."
categories: "common"
---
> Maggiori informazioni: <https://xiph.org/flac>.

- Converte un file wav in un file flac (questo creerà un file flac nella medesima posizione del file wav):

```bash
flac percorso/al/file.wav
```

- Codifica un file wav in flac, specificando il nome del risultato:

```bash
flac -o percorso/al/file_compresso.flac percorso/al/file_originale.wav
```

- Decodifica un file wav in flac, specificando il nome del risultato:

```bash
flac -d -o percorso/al/file_decompresso.wav percorso/al/file_originale.flac
```

- Controlla che un file flac sia codificato correttamente:

```bash
flac -t percorso/al/file.flac
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Agno94](mailto:agnophi@gmail.com) | ffprobe, flac, id3tag, opusenc, vlc, wget, youtube-dl: add Italian translation (#4869) | 2020-11-02T13:07:44 | [e9eb628533b3](https://github.com/tldr-pages/tldr/commit/e9eb628533b31c09c5951ffa57f4194be88d8f63)

