---
author: ['Frank Benedikt', 'Dario Vladović', 'marchersimon']
date: 1619262596
title: "chmod, TLDR Pages"
description: "chmod, Ändere die Zugriffsberechtigungen einer Datei oder eines Verzeichnisses."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/chmod>.

- Gib dem Besitzer einer Datei ([u]ser) das Recht, sie auszuführen (e[x]ecute):

```bash
chmod u+x pfad/zu/datei
```

- Gib dem Besitzer ([u]ser) Rechte zum Lesen ([r]ead) und Schreiben ([w]rite) einer Datei / einem Verzeichnis:

```bash
chmod u+rw pfad/zu/datei_oder_verzeichnis
```

- Entferne die Ausführrechte (e[x]ecute) der Besitzer[g]ruppe:

```bash
chmod g-x pfad/zu/datei
```

- Gib [a]llen Benutzern Rechte zum Lesen ([r]ead) und Ausführen (e[x]ecute) einer Datei:

```bash
chmod a+rx pfad/zu/datei
```

- Gib anderen ([o]thers) (nicht in der Besitzer[g]ruppe) die gleichen Rechte wie der Besitzer[g]ruppe:

```bash
chmod o=g pfad/zu/datei
```

- Entferne alle Rechte der anderen ([o]thers):

```bash
chmod o= pfad/zu/datei
```

- Ändere Rechte rekursiv, indem der Besitzer[g]ruppe und anderen ([o]thers) die Rechte zum Schreiben ([w]rite) geben werden:

```bash
chmod -R g+w,o+w pfad/zu/verzeichnis
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chmod: change more information link (#5547) | 2021-03-29T22:28:18 | [db38dff0e9db](https://github.com/tldr-pages/tldr/commit/db38dff0e9db1d880e7406df340d16509470fbbb)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Frank Benedikt](mailto:63481435+FrankBG67@users.noreply.github.com) | German translation: alias, bash, borg, cd, chmod, chromium, chsh, convert, exa (#4132) Co-authored-by: Zlatan Vasović [...] | 2020-06-29T23:59:34 | [9aa5907281cb](https://github.com/tldr-pages/tldr/commit/9aa5907281cbaa7a0ee08b5c330c660d779282c7)

