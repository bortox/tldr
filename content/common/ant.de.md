---
author: ['Michael Schwarz']
date: 1635464874
title: "ant, TLDR Pages"
description: "ant, Apache Ant."
categories: "common"
---
> Tool zum Bauen und Verwalten von Projekten, die auf Java basieren.

> Weitere Informationen: <https://ant.apache.org>.

- Baue ein Projekt mit der Standard build-Datei `build.xml`:

```bash
ant
```

- Baue ein Projekt mit einer anderen build-Datei als `build.xml`:

```bash
ant -f buildfile.xml
```

- Zeige Informationen über mögliche targets für dieses Projekt:

```bash
ant -p
```

- Zeige Debugging-Informationen:

```bash
ant -d
```

- Führe alle targets aus, die nicht von fehlgeschlagenen targets abhängen:

```bash
ant -k
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Michael Schwarz](mailto:michael089+github@outlook.de) | ant: add German translation (#7262) | 2021-10-29T01:47:54 | [d3bb0312a275](https://github.com/tldr-pages/tldr/commit/d3bb0312a27547ec2ae00fc9ef34bf765ccd622a)

