---
author: ['MeerBiene', 'lincc']
date: 1643487459
title: "aptitude"
description: "aptitude, Debian und Ubuntu Paket Management Tool."
categories: "linux"
---
> Weitere Informationen: <https://manpages.debian.org/latest/aptitude/aptitude.8.html>.

- Synchronisiere die Paketliste und verfügbaren Versionen. Dieser Command sollte zuerst ausgeführt werden bevor weitere aptitude Commands ausgeführt werden:

```bash
aptitude update
```

- Installiere ein neues Paket und seine Abhängigkeiten:

```bash
aptitude install paket
```

- Suche nach einem Paket:

```bash
aptitude search paket
```

- Suche nach einem installierten Paket (`?installed` ist ein aptitude Suchbegriff):

```bash
aptitude search ?installed (paket)
```

- Entferne ein Paket und alle Abhängigkeiten:

```bash
aptitude remove paket
```

- Aktualisiere installierte Pakete auf die neusten Versionen:

```bash
aptitude upgrade
```

- Aktualisiere installierte Pakete (wie `aptitude upgrade`), inklusive obsoleter Pakete und installiere zusätzliche Pakete um die neuen Paket Abhängigkeiten zu erfüllen:

```bash
aptitude full-upgrade
```

- Friere ein installiertes Paket ein und verhindere, dass es automatisch aktualisiert wird:

```bash
aptitude hold '?installed(paket)'
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

