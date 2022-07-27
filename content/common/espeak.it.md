---
author: ['Marco Bonelli']
date: 1570281951
title: "espeak, TLDR Pages"
description: "espeak, Usa la sintesi vocale per parlare tramite il dispositivo audio di output predefinito."
categories: "common"
---
> Maggiori informazioni: <http://espeak.sourceforge.net>.

- Pronuncia una frase ad alta voce:

```bash
espeak "Mi piace andare in bici."
```

- Pronuncia il contenuto di un file ad alta voce:

```bash
espeak -f nome_file
```

- Salva l'output su un file audio WAV, invece che parlare direttamente:

```bash
espeak -w nome_file.wav "È GNU più Linux."
```

- Usa una voce differente:

```bash
espeak -v voce
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | espeak: add Italian translation. | 2019-10-05T15:25:51 | [c3ba2a1ad16f](https://github.com/tldr-pages/tldr/commit/c3ba2a1ad16fcb2d041b2b7db1b522235df34bbe)

