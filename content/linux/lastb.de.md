---
author: ['Margu']
date: 1634837492
title: "lastb"
description: "lastb, Zeigt eine Liste der zuletzt angemeldeten Benutzer an."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/lastb>.

- Zeige eine Liste aller zuletzt angemeldeten Benutzer an:

```bash
sudo lastb
```

- Zeige eine Liste aller zuletzt angemeldeten Benutzer seit einem bestimmten Zeitpunkt an:

```bash
sudo lastb --since YYYY-MM-DD
```

- Zeige eine Liste aller zuletzt angemeldeten Benutzer bis zu einem bestimmten Zeitpunkt an:

```bash
sudo lastb --until YYYY-MM-DD
```

- Zeige eine Liste aller angemeldeten Benutzer zu einem bestimmten Zeitpunkt an:

```bash
sudo lastb --present hh:mm
```

- Zeige eine Liste aller zuletzt angemeldeten Benutzer und übersetze die IP zu einem Hostnamen:

```bash
sudo lastb --dns
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Margu](mailto:44941663+Margu86@users.noreply.github.com) | logwatch, lastlog, line, logsave, lsmod, lastb, lastcomm, ldconfig, ldd: add German translation (#6996) | 2021-10-21T19:31:32 | [b37b6755b8c0](https://github.com/tldr-pages/tldr/commit/b37b6755b8c075ef4ec8996074da03a86a568342)

