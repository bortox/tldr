---
author: ['3ncy', 'marchersimon']
date: 1659075216
title: "nologin, TLDR Pages"
description: "nologin, Alternative Shell, die verhindert, dass sich ein Benutzer einloggt."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/nologin.5>.

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
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[3ncy](mailto:53367954+3ncy@users.noreply.github.com) | google-chrome, ipcalc, nologin, ...: add German translation (#7290) | 2021-11-02T10:57:07 | [c45572ce7377](https://github.com/tldr-pages/tldr/commit/c45572ce7377dffa45e0791c419a6f17af40865a)

