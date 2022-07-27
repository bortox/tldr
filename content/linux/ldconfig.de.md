---
author: ['Margu', 'Daniel']
date: 1634914980
title: "ldconfig, TLDR Pages"
description: "ldconfig, Symbolische Verknüpfungen und Zwischenspeicher für Abhängigkeiten von gemeinsam genutzten Bibliotheken konfigurieren."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/ldconfig>.

- Aktualisiere symbolische Verknüpfungen und erstelle den Zwischenspeicher neu (wird normalerweise ausgeführt, wenn eine neue Bibliothek installiert wird):

```bash
sudo ldconfig
```

- Aktualisiere die symbolischen Verknüpfungen für ein bestimmtes Verzeichnis:

```bash
sudo ldconfig -n pfad/zu/verzeichnis
```

- Gib die Bibliotheken im Zwischenspeicher aus und prüfe ob eine bestimmte Bibliothek vorhanden ist:

```bash
ldconfig -p | grep bibliotheksname
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[Margu](mailto:44941663+Margu86@users.noreply.github.com) | logwatch, lastlog, line, logsave, lsmod, lastb, lastcomm, ldconfig, ldd: add German translation (#6996) | 2021-10-21T19:31:32 | [b37b6755b8c0](https://github.com/tldr-pages/tldr/commit/b37b6755b8c075ef4ec8996074da03a86a568342)

