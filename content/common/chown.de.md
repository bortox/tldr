---
author: ['Dario Vladović', 'marchersimon']
date: 1619262596
title: "chown"
description: "chown, Ändere den Besitzer und die Besitzergruppe von Dateien und Verzeichnissen."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/chown>.

- Ändere den Besitzer einer Datei/eines Verzeichnisses:

```bash
chown benutzer pfad/zu/datei_oder_verzeichnis
```

- Ändere den Besitzer und die Besitzergruppe einer Datei/eines Verzeichnisses:

```bash
chown benutzer:gruppe pfad/zu/datei_oder_verzeichnis
```

- Ändere den Besitzer eines Verzeichnisses rekursiv:

```bash
chown -R benutzer pfad/zu/verzeichnis
```

- Ändere den Besitzer eines symbolischen Links:

```bash
chown -h benutzer pfad/zu/symlink
```

- Ändere den Besitzer einer Datei/eines Verzeichnisses, damit sie/es mit einer Referenzdatei übereinstimmt:

```bash
chown --reference=pfad/zu/referenzdatei_oder_verzeichnis pfad/zu/datei_oder_verzeichnis
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chown: add more information link (#5555) | 2021-03-30T15:29:42 | [8d147522d127](https://github.com/tldr-pages/tldr/commit/8d147522d127f65aca087b791bf2deb46a43f59d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)

