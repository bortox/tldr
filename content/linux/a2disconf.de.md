---
author: ['Thomas Christlieb']
date: 1633659892
title: "a2disconf, TLDR Pages"
description: "a2disconf, Deaktiviert eine Apache Konfigurationsdatei auf Debian-basierten Betriebssystemen."
categories: "linux"
---
> Weitere Informationen: <https://manpages.debian.org/latest/apache2/a2disconf.8.en.html>.

- Deaktiviere eine Konfigurationsdatei:

```bash
sudo a2disconf konfigurationsdatei
```

- Zeige keine Informationsnachrichten an:

```bash
sudo a2disconf --quiet konfigurationsdatei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Thomas Christlieb](mailto:thomaschristlieb@hotmail.com) | a2disconf: add German translation (#6864) | 2021-10-08T04:24:52 | [c7b138c8edec](https://github.com/tldr-pages/tldr/commit/c7b138c8edecbcc85297fc9e384e3d72476861ff)

