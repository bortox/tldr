---
author: ['marchersimon', 'Mastercuber']
date: 1659075216
title: "alien, TLDR Pages"
description: "alien, Ein Installations-Paket in ein anderes Format umwandeln."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/alien>.

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
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Mastercuber](mailto:mr_w@posteo.de) | alien, abbr: add German translation (#7651) | 2022-02-03T11:09:52 | [07c853b70af1](https://github.com/tldr-pages/tldr/commit/07c853b70af1e865ef69d29251ea09fc0442dc63)

