---
author: ['Axel Navarro', 'Leandro Meleti']
date: 1641649180
title: "dpkg"
description: "dpkg, Debian Paketmanager."
categories: "linux"
---
> Manche Unterbefehle wie `dpkg deb` sind separat dokumentiert.

> Weitere Informationen: <https://manpages.debian.org/latest/dpkg/dpkg.html>.

- Installiere ein Paket:

```bash
dpkg -i pfad/zu/datei.deb
```

- Entferne ein Paket:

```bash
dpkg -r paketname
```

- Liste installierte Pakete auf:

```bash
dpkg -l muster
```

- Liste die Inhalte eines Pakets auf:

```bash
dpkg -L paketname
```

- Liste die Inhalte einer lokalen Paketdatei auf:

```bash
dpkg -c pfad/zu/datei.deb
```

- Finde heraus welche Pakete eine Datei besitzen:

```bash
dpkg -S dateiname
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Leandro Meleti](mailto:leandromeleti97@hotmail.com) | dpgk: add German translation (#6796) | 2021-10-06T20:30:22 | [a589fd38e08d](https://github.com/tldr-pages/tldr/commit/a589fd38e08d2562fa96f923d9ee83680e2de1a3)

