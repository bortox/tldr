---
author: ['marchersimon', 'Lucas Gabriel Schneider', 'Felix Brilej', 'syleung']
date: 1633351190
title: "sshpass, TLDR Pages"
description: "sshpass, Stelle SSH Passwörtern bereit."
categories: "common"
---
> Weitere Informationen: <https://manned.org/sshpass>.

- Stelle eine Verbindung zu einem externen Server über ein Passwort aus einem Datei-Objekt her (in diesem Fall stdin):

```bash
sshpass -d 0 ssh benutzer@server
```

- Stelle eine Verbindung zu einem externen Server mit Hilfe eines Passworts bei automatischer Akzeptierung von unbekannten SSH Schlüsseln her:

```bash
sshpass -p passwort ssh -o StrictHostKeyChecking=no benutzer@server
```

- Stelle eine Verbindung zu einem externen Server mit Hilfe eines Passworts aus der ersten Zeile einer Datei bei automatischer Akzeptierung von unbekannten SSH Schlüsseln mit anschließender Ausführung eines Befehls her:

```bash
sshpass -f pfad/zu/datei ssh -o StrictHostKeyChecking=no benutzer@server "befehl"
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | ssh*: Add German translation (#4835) | 2020-10-28T19:28:11 | [8bd6dd5ffad1](https://github.com/tldr-pages/tldr/commit/8bd6dd5ffad1ed34653270c3ebbed2387c41beac)

