---
author: ['Margu']
date: 1634837492
title: "logwatch, TLDR Pages"
description: "logwatch, Fasst viele verschiedene Logs für gängige Dienste (z.B. Apache, pam_unix, sshd, usw.) in einem einzelnen Bericht zusammen."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/logwatch>.

- Analysiere Logs für einen Zeitraum mit einer bestimmten Detailtiefe:

```bash
logwatch --range yesterday|today|all|help --detail low|medium|others'
```

- Beschränke den Bericht auf Informationen zu einem ausgewählten Dienst:

```bash
logwatch --range all --service apache|pam_unix|etc
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Margu](mailto:44941663+Margu86@users.noreply.github.com) | logwatch, lastlog, line, logsave, lsmod, lastb, lastcomm, ldconfig, ldd: add German translation (#6996) | 2021-10-21T19:31:32 | [b37b6755b8c0](https://github.com/tldr-pages/tldr/commit/b37b6755b8c075ef4ec8996074da03a86a568342)

