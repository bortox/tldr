---
author: ['Dario Vladović', 'bl-ue', 'marchersimon']
date: 1626631245
title: "dd, TLDR Pages"
description: "dd, Konvertiere und kopiere eine Datei."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/dd>.

- Erstelle ein bootbares USB-Laufwerk von einer isohybriden Datei (wie `archlinux-xxxx.iso`) und zeige den Fortschritt an:

```bash
dd if=pfad/zu/datei.iso of=/dev/laufwerk status=progress
```

- Klone ein USB-Laufwerk in ein anderes in 4MiB Blöcken, ignoriere Fehler und zeige den Fortschritt an:

```bash
dd if=/dev/quell_laufwerk of=/dev/ziel_laufwerk bs=4M conv=noerror status=progress
```

- Erstelle eine Datei mit 100 zufälligen Bytes mithilfe des Zufall-Treibers des Kernels:

```bash
dd if=/dev/urandom of=pfad/zu/datei bs=100 count=1
```

- Teste die Schreibgeschwindigkeit eines Laufwerks:

```bash
dd if=/dev/zero of=pfad/zu/1GB_datei bs=1024 count=1000000
```

- Erstelle ein System-Backup als IMG Datei und zeige den Fortschritt an:

```bash
dd if=/dev/laufwerk of=pfad/zu/datei.img status=progress
```

- Stelle ein Laufwerk aus einer IMG Datei wieder her und zeige den Fortschritt an:

```bash
dd if=pfad/zu/datei.img of=/dev/laufwerk status=progress
```

- Überprüfe den Fortschritt eines laufenden dd-Prozsses (Führe diesen Befehl von einer anderen Shell aus):

```bash
kill -USR1 $(pgrep ^dd)
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, ansible-galaxy, convert, dd, exa, fuck, git-*, gpg, ls, mv: sync German page (#6226) | 2021-07-18T20:00:45 | [1dcdac60df90](https://github.com/tldr-pages/tldr/commit/1dcdac60df901488a051d3f2f2e4171a158be904)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dd: change more information link (#5548) | 2021-03-30T12:18:12 | [4a95098a45d0](https://github.com/tldr-pages/tldr/commit/4a95098a45d072a9e1204208ff6dff13ae51c693)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)

