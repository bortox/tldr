---
author: ['Margu']
date: 1634837492
title: "lastcomm, TLDR Pages"
description: "lastcomm, Zeige die zuletzt ausgeführten Befehle an."
categories: "linux"
---
> Weitere Informationen: <https://manpages.debian.org/stable/acct/lastcomm.1.en.html>.

- Gib Informationen zu allen Befehlen in acct aus (Aufzeichnungsdatei):

```bash
lastcomm
```

- Zeige die ausgeführten Befehle eines bestimmten Benutzers an:

```bash
lastcomm --user benutzer
```

- Zeige Informationen zu einem bestimmten Befehl an, der auf dem System ausgeführt wird:

```bash
lastcomm --command befehl
```

- Zeige Informationen zu Befehlen an, die auf einem bestimmten Terminal ausgeführt wurden:

```bash
lastcomm --tty terminal_name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Margu](mailto:44941663+Margu86@users.noreply.github.com) | logwatch, lastlog, line, logsave, lsmod, lastb, lastcomm, ldconfig, ldd: add German translation (#6996) | 2021-10-21T19:31:32 | [b37b6755b8c0](https://github.com/tldr-pages/tldr/commit/b37b6755b8c075ef4ec8996074da03a86a568342)

