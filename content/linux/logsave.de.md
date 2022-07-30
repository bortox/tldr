---
author: ['Margu']
date: 1634837492
title: "logsave"
description: "logsave, Speichert die Ausgabe eines Befehls in eine Logdatei."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/logsave>.

- Führe einen Befehl mit angegebenen Argumenten aus und speichere die Ausgabe in eine Logdatei:

```bash
logsave pfad/zu/logdatei befehl
```

- Übernimm die Eingabe der Standardeingabe und speichere diese in eine Logdatei:

```bash
logsave logdatei -
```

- Hänge die Ausgabe an eine Logdatei an, anstatt deren aktuellen Inhalt zu ersetzen:

```bash
logsave -a logfile befehl
```

- Zeige die ausführliche Ausgabe an:

```bash
logsave -v logfile befehl
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Margu](mailto:44941663+Margu86@users.noreply.github.com) | logwatch, lastlog, line, logsave, lsmod, lastb, lastcomm, ldconfig, ldd: add German translation (#6996) | 2021-10-21T19:31:32 | [b37b6755b8c0](https://github.com/tldr-pages/tldr/commit/b37b6755b8c075ef4ec8996074da03a86a568342)

