---
author: ['Mastercuber']
date: 1643882992
title: "alien, TLDR Pages"
description: "alien, Ein Installations-Paket in ein anderes Format umwandeln."
categories: "linux"
---
> Mehr Informationen: <https://manned.org/alien>.

- Ein spezifisches Installationspaket in das Debian Format umwandeln (`.deb` Erweiterung)

```bash
sudo alien --to-deb pfad/zum/paket
```

- Ein spezifisches Installationspaket in das Red Hat Format umwandeln (`.rpm` Erweiterung)

```bash
sudo alien --to-rpm pfad/zum/paket
```

- Ein spezifisches Installationspaket in das Slackware Format umwandeln (`.tgz` Erweiterung)

```bash
sudo alien --to-tgz pfad/zum/paket
```

- Ein spezifisches Installationspaket in das Debian Format umwandeln und auf dem System installieren

```bash
sudo alien --to-deb --install pfad/zum/paket
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Mastercuber](mailto:mr_w@posteo.de) | alien, abbr: add German translation (#7651) | 2022-02-03T11:09:52 | [07c853b70af1](https://github.com/tldr-pages/tldr/commit/07c853b70af1e865ef69d29251ea09fc0442dc63)

