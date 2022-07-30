---
author: ['Marco Bonelli', 'marchersimon']
date: 1633112881
title: "exiftool"
description: "exiftool, Leggi e scrivi metadati nei file."
categories: "common"
---
> Maggiori informazioni: <https://exiftool.org>.

- Rimuovi tutti i metadati EXIF dai file specificati:

```bash
exiftool -All= file1 file2 ...
```

- Muovi avanti di 1 ora la data in cui sono state scattate tutte le foto contenute in una directory:

```bash
exiftool "-AllDates+=0:0:0 1:0:0" percorso/a/directory
```

- Muovi indietro di 1 giorno e 2 ore la data in cui sono state scattate tutte le immagini JPEG:

```bash
exiftool "-AllDates-=0:0:1 2:0:0" -ext jpg
```

- Cambia solo il campo `DateTimeOriginal` sottraendo 1.5 ore e non tenere file di backup:

```bash
exiftool -DateTimeOriginal-=1.5 -overwrite_original
```

- Rinomina ricorsivamente tutti i file JPEG in una directory in base al campo `DateTimeOriginal`:

```bash
exiftool '-filename<DateTimeOriginal' -d %Y-%m-%d_%H-%M-%S%%lc.%%e percorso/a/directory -r -ext jpg
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:marco@mebeim.net) | exiftool: add Italian translation. | 2019-10-05T15:25:51 | [83c10d4f95b4](https://github.com/tldr-pages/tldr/commit/83c10d4f95b40c9e2edabb05418a0ff4d8b27c5c)

