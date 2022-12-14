---
author: ['bl-ue', 'Felix Brilej', 'marchersimon']
date: 1619262596
title: "sshfs"
description: "sshfs, Dateisystem Client für SSH."
categories: "common"
---
> Weitere Informationen: <https://github.com/libfuse/sshfs>.

- Hänge ein externes Verzeichnis ein:

```bash
sshfs benutzer@externer_server:externes_verzeichnis lokales_einhänge_verzeichnis
```

- Hänge ein externes Verzeichnis aus:

```bash
umount lokaler_einhänge_verzeichnis
```

- Hänge ein externes Verzeichnis unter einem bestimmten Port ein:

```bash
sshfs benutzer@externer_server:externes_verzeichnis -p 2222
```

- Verwende Komprimierung:

```bash
sshfs benutzer@externer_server:externes_verzeichnis -C
```

- Folge symbolischen Links:

```bash
sshfs -o follow_symlinks benutzer@externer_server:externes_verzeichnis lokaler_einhänge_verzeichnis
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | ssh*: Add German translation (#4835) | 2020-10-28T19:28:11 | [8bd6dd5ffad1](https://github.com/tldr-pages/tldr/commit/8bd6dd5ffad1ed34653270c3ebbed2387c41beac)

