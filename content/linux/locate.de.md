---
author: ['Margu', 'Daniel']
date: 1634914980
title: "locate, TLDR Pages"
description: "locate, Zum schnellen Finden von Dateinamen."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/locate>.

- Suche nach Dateien in der Datenbank. Hinweis: Die Datenbank wird periodisch aktualisiert (für gewöhnlich täglich oder wöchentlich):

```bash
locate muster
```

- Suche nach Dateien mit dem exakten Dateinamen. (Ein Muster ohne Platzhalterzeichen wird als `*muster*` interpretiert):

```bash
locate */dateiname
```

- Aktualisiere die Datenbank. Dies ist nötig, falls kürzlich hinzugefügte Dateien gefunden werden sollen:

```bash
sudo updatedb
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[Margu](mailto:44941663+Margu86@users.noreply.github.com) | locate: add German translation (#6991) | 2021-10-13T18:37:44 | [8b489dff7ce1](https://github.com/tldr-pages/tldr/commit/8b489dff7ce160279c835121e85e029f32b85872)

