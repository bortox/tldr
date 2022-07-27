---
author: ['Margu', 'marchersimon']
date: 1634849018
title: "lastlog, TLDR Pages"
description: "lastlog, Zeigt den letzten Login aller Benutzer oder eines bestimmten Benutzers an."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/lastlog>.

- Zeige den letzten Login aller Benutzer an:

```bash
lastlog
```

- Zeige den lastlog Datensatz des angegebenen Benutzers an:

```bash
lastlog --user benutzername
```

- Zeige Datensätze älter als 7 Tage an:

```bash
lastlog --before 7
```

- Zeige Datensätze jünger als 3 Tage an:

```bash
lastlog --time 3
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | lastlog: refresh (#7133) | 2021-10-21T22:43:38 | [254a2f9ae7f7](https://github.com/tldr-pages/tldr/commit/254a2f9ae7f7eb67b661ff3d17f097159ac8a397)
[Margu](mailto:44941663+Margu86@users.noreply.github.com) | logwatch, lastlog, line, logsave, lsmod, lastb, lastcomm, ldconfig, ldd: add German translation (#6996) | 2021-10-21T19:31:32 | [b37b6755b8c0](https://github.com/tldr-pages/tldr/commit/b37b6755b8c075ef4ec8996074da03a86a568342)

