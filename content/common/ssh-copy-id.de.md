---
author: ['Felix Brilej', 'syleung', 'marchersimon']
date: 1633351190
title: "ssh-copy-id"
description: "ssh-copy-id, Installiere den öffentlichen Teil eines SSH Schlüssels in der `authorized_keys` Datei auf einem externen Server."
categories: "common"
---
> Weitere Informationen: <https://manned.org/ssh-copy-id>.

- Kopiere den eigenen öffentlichen SSH Schlüssels zu einem externen Server:

```bash
ssh-copy-id benutzer@externer_server
```

- Kopiere den angegebenen öffentlichen SSH Schlüssels zu einem externen Server:

```bash
ssh-copy-id -i pfad/zu/öffentlichem_schlüssel benutzer@externer_server
```

- Kopiere den angegeben öffentlichen SSH Schlüssels zu einem externen Server unter Angabe eines bestimmten SSH Ports:

```bash
ssh-copy-id -i pfad/zu/öffentlichem_schlüssel -p port benutzer@externer_server
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | ssh*: Add German translation (#4835) | 2020-10-28T19:28:11 | [8bd6dd5ffad1](https://github.com/tldr-pages/tldr/commit/8bd6dd5ffad1ed34653270c3ebbed2387c41beac)

