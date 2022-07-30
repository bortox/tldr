---
author: ['marchersimon']
date: 1619262596
title: "clear"
description: "clear, Leert den Bildschirm eines Terminals."
categories: "common"
---
> Weitere Informationen: <https://manned.org/clear>.

- Leere den Bildschirm (äquivalent zu Strg+L in einer Bash Shell):

```bash
clear
```

- Leere den Bildschirm, aber erhalte den Rückscroll-Puffer des Terminals:

```bash
clear -x
```

- Lege den Typ des zu leerenden Terminals fest (Standardwert ist die Umgebungsvariable $TERM):

```bash
clear -T typ_des_terminals
```

- Zeige die Version von `ncurses` an, die von `clear` benutzt wird:

```bash
clear -V
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | clear: add link | 2021-04-18T16:33:27 | [907b82779088](https://github.com/tldr-pages/tldr/commit/907b827790882ee9086eb4d20cf8e3059343048a)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)

