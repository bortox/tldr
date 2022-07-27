---
author: ['Felix Brilej', 'bl-ue', 'marchersimon']
date: 1619262596
title: "cradle elastic, TLDR Pages"
description: "cradle elastic, Verwalte ElasticSearch Instanzen einer Cradle Instanz."
categories: "common"
---
> Weitere Informationen: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#elastic>.

- Entleere den ElasticSearch Index:

```bash
cradle elastic flush
```

- Entleere den ElasticSearch Index für ein bestimmtes Paket:

```bash
cradle elastic flush paket
```

- Sende ein ElasticSearch Schema ab:

```bash
cradle elastic map
```

- Sende ein ElasticSearch Schema für ein bestimmtes Paket ab:

```bash
cradle elastic map paket
```

- Befülle die ElasticSearch Indizes für alle Pakete:

```bash
cradle elastic populate
```

- Befülle die ElasticSearch Indizes für ein bestimmtes Paket:

```bash
cradle elastic populate paket
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | cradle*: add German translation (#4841) | 2020-10-28T18:57:00 | [6155aa9a2aac](https://github.com/tldr-pages/tldr/commit/6155aa9a2aac24323fe56ae998081b9b626a9509)

