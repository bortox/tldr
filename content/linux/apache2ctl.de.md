---
author: ['MeerBiene', 'lincc']
date: 1643487459
title: "apache2ctl"
description: "apache2ctl, Das CLI Tool um den Apache HTTP Web Server zu administrieren."
categories: "linux"
---
> Dieser Befehl wird mit Debian-basierten Betriebssystemen geliefert, für RHEL siehe `httpd`.

> Weitere Informationen: <https://manpages.debian.org/latest/apache2/apache2ctl.8.en.html>.

- Starte den Apache daemon. Gibt einen Fehler aus, wenn er bereits läuft:

```bash
sudo apache2ctl start
```

- Stoppe den Apache Daemon:

```bash
sudo apache2ctl stop
```

- Starte den Apache Daemon neu:

```bash
sudo apache2ctl restart
```

- Überprüfe die Syntax einer Konfigurationsdatei:

```bash
sudo apache2ctl -t
```

- Liste alle geladenen Module auf:

```bash
sudo apache2ctl -M
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

