---
author: ['marchersimon', 'Felix Brilej', 'bl-ue', 'lincc']
date: 1636372515
title: "aws s3, TLDR Pages"
description: "aws s3, CLI für AWS S3. AWS S3 stellt Speicherplatz in der Cloud zur Verfügung."
categories: "common"
---
> Weitere Informationen: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3/index.html>.

- Liste alle Objekte in einem Bucket auf:

```bash
aws s3 ls bucket_name
```

- Synchronisiere Dateien und Verzeichnissen zu einem Bucket:

```bash
aws s3 sync pfad/zu/datei_oder_verzeichnis s3://bucket_name
```

- Synchronisiere Dateien und Verzeichnissen von einem Bucket:

```bash
aws s3 sync s3://bucket_name pfad/zu/ziel
```

- Synchronisiere Dateien und Verzeichnissen mit Ausnahmen:

```bash
aws s3 sync pfad/zu/datei_oder_verzeichnis s3://bucket_name --exclude pfad/zu/datei --exclude pfad/zu/verzeichnis/*
```

- Entferne ein Objekt von einem Bucket:

```bash
aws s3 rm s3://bucket/pfad/zu/datei
```

- Probelauf eines angegeben Kommandos ohne diesen auszuführen:

```bash
aws s3 befehl --dryrun
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | aws*: add German translation (#4827) | 2020-10-24T15:27:02 | [455f988c81a2](https://github.com/tldr-pages/tldr/commit/455f988c81a21f9d47983d5b1607d3d03b216db4)

