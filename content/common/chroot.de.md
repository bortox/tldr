---
author: ['Dario Vladović', 'marchersimon']
date: 1619262596
title: "chroot"
description: "chroot, Führe einen Befehl oder eine interaktive Shell mit einem speziellen root-Verzeichnis aus."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/chroot>.

- Führe einen Befehl mit einem neuen root-Verzeichnis aus:

```bash
chroot pfad/zu/root_verzeichnis befehl
```

- Lege einen Benutzer und eine Gruppe (ID oder Name) fest, der benutzt werden soll:

```bash
chroot --userspec=benutzer:gruppe
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chroot: add more information link (#5602) | 2021-03-30T15:50:36 | [b8f38025f36c](https://github.com/tldr-pages/tldr/commit/b8f38025f36c58be3d109949f4badf9e062b43e0)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)

