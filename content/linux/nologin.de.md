---
author: ['3ncy']
date: 1635847027
title: "nologin, TLDR Pages"
description: "nologin, Alternative Shell, die verhindert, dass sich ein Benutzer einloggt."
categories: "linux"
---
- Setze die Login-Shell eines Benutzers auf `nologin`, um zu verhindern, dass der Benutzer sich anmeldet:

```bash
chsh -s user nologin
```

- Passe die Nachricht für Benutzer mit Login-Shell `nologin` an:

```bash
echo "nachricht" > /etc/nologin.txt
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[3ncy](mailto:53367954+3ncy@users.noreply.github.com) | google-chrome, ipcalc, nologin, ...: add German translation (#7290) | 2021-11-02T10:57:07 | [c45572ce7377](https://github.com/tldr-pages/tldr/commit/c45572ce7377dffa45e0791c419a6f17af40865a)

