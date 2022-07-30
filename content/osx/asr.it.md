---
author: ['Carlo Federico Vescovo', 'Kyle']
date: 1629747204
title: "asr"
description: "asr, Ripristina (copia) un'immagine disco dentro a un volume."
categories: "osx"
---
> Il nome del comando sta per Apple Software Restore (software di ripristino Apple).

> Maggiori informazioni: <https://www.unix.com/man-page/osx/8/asr/>.

- Ripristina un'immagine disco su un volume specifico:

```bash
sudo asr restore --source nome_immagine.dmg --target percorso/del/volume
```

- Distruggi il volume specifico prima di ripristinare:

```bash
sudo asr restore --source nome_immagine.dmg --target percorso/del/volume --erase
```

- Salta la verifica dopo il ripristino:

```bash
sudo asr restore --source nome_immagine.dmg --target percorso/del/volume --noverify
```

- Clona i volumi senza utilizzare un'immagine disco intermedia:

```bash
sudo asr restore --source percorso/del/volume --target percorso/del/volume/clonato
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Carlo Federico Vescovo](mailto:vescovocarlofederico@gmail.com) | asr, base64, caffeinate, diskutil: add Italian translation (#4451) | 2020-10-05T16:32:45 | [a0d7ca3f3e7e](https://github.com/tldr-pages/tldr/commit/a0d7ca3f3e7e678c8c388b6158c3225eca27fee1)

