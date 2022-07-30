---
author: ['Axel Navarro', 'Thomas Christlieb']
date: 1641649180
title: "a2query"
description: "a2query, Zeigt Apache Laufzeitkonfigurationen auf Debian-basierten Betriebssystemen an."
categories: "linux"
---
> Weitere Informationen: <https://manpages.debian.org/latest/apache2/a2query.html>.

- Zeige aktivierte Apache Module an:

```bash
sudo a2query -m
```

- Prüfe, ob ein bestimmtes Modul installiert ist:

```bash
sudo a2query -m modulname
```

- Zeige aktivierte virtuelle Hosts an:

```bash
sudo a2query -s
```

- Zeige das aktuell aktivierte Multi-Processing-Modul an:

```bash
sudo a2query -M
```

- Zeige die Apache Versionsnummer an:

```bash
sudo a2query -v
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Thomas Christlieb](mailto:thomaschristlieb@hotmail.com) | a2dismod, a2dissite, a2enmod, a2ensite, a2query: add German translation (#6866) | 2021-10-08T14:41:38 | [1bb3949a2e05](https://github.com/tldr-pages/tldr/commit/1bb3949a2e05431e7107ce200bc34bcc23b71a14)

