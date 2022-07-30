---
author: ['Frank Benedikt', 'Lucas Gabriel Schneider', 'Daniel', 'marchersimon']
date: 1634914980
title: "bash"
description: "bash, Bourne-Again SHell."
categories: "common"
---
> `sh`-kompatibler Kommandozeilen-Interpreter.

> Weitere Informationen: <https://gnu.org/software/bash/>.

- Interaktive Shell starten:

```bash
bash
```

- Führe einen Befehl aus:

```bash
bash -c "befehl"
```

- Führe Befehle aus einer Datei aus:

```bash
bash pfad/zu/datei.sh
```

- Führe Befehle aus einer Datei aus und protokolliere alle ausgeführten Befehle an das Terminal:

```bash
bash -x pfad/zu/datei.sh
```

- Führe Befehle aus einer Datei aus und stoppe beim ersten Fehler:

```bash
bash -e pfad/zu/datei.sh
```

- Führe Befehle von stdin aus:

```bash
bash -s
```

- Gib die Version von bash aus (verwende `echo $BASH_VERSION`, um nur die Versionszeichenkette anzuzeigen):

```bash
bash --version
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Frank Benedikt](mailto:63481435+FrankBG67@users.noreply.github.com) | German translation: alias, bash, borg, cd, chmod, chromium, chsh, convert, exa (#4132) Co-authored-by: Zlatan Vasović [...] | 2020-06-29T23:59:34 | [9aa5907281cb](https://github.com/tldr-pages/tldr/commit/9aa5907281cbaa7a0ee08b5c330c660d779282c7)

