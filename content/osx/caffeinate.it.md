---
author: ['Carlo Federico Vescovo', 'Kyle']
date: 1629747204
title: "caffeinate"
description: "caffeinate, Impedisci al mac di sospendersi."
categories: "osx"
---
> Maggiori informazioni: <https://ss64.com/osx/caffeinate.html>.

- Impedisci la sospensione per un'ora (3600 secondi):

```bash
caffeinate -u -t 3600
```

- Impedisci la sospensione fino al completamento dell'esecuzione di un comando:

```bash
caffeinate -s comando
```

- Impedisci la sospensione fino alla pressione della combinazione di tasti Ctrl-C:

```bash
caffeinate -i
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Carlo Federico Vescovo](mailto:vescovocarlofederico@gmail.com) | asr, base64, caffeinate, diskutil: add Italian translation (#4451) | 2020-10-05T16:32:45 | [a0d7ca3f3e7e](https://github.com/tldr-pages/tldr/commit/a0d7ca3f3e7e678c8c388b6158c3225eca27fee1)

