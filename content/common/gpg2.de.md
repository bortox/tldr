---
author: ['marchersimon', 'Daniel']
date: 1634914980
title: "gpg2, TLDR Pages"
description: "gpg2, GNU Privacy Guard 2."
categories: "common"
---
> Siehe `gpg` für GNU Privacy Guard 1.

> Weitere Informationen: <https://docs.releng.linuxfoundation.org/en/latest/gpg.html>.

- Liste alle importierten Schlüssel auf:

```bash
gpg2 --list-keys
```

- Verschlüssle eine bestimme Datei für einen bestimmten Empfänger und schreibe den Output in eine neue `.gpg` Datei:

```bash
gpg2 --encrypt --recipient hans@beispiel.de pfad/zu/datei.txt
```

- Verschlüssle eine bestimmte Datei nur mit einem Passwort und schreibe den Output in eine neue `.gpg` Datei:

```bash
gpg2 --symmetric pfad/zu/datei.txt
```

- Verschlüssle eine bestimmte Datei und schreibe das Ergebnis auf STDOUT:

```bash
gpg2 --decrypt pfad/zu/datei.txt.gpg
```

- Importiere einen öffentlichen Schlüssel:

```bash
gpg2 --import pfad/zu/öffentlichem_schlüssel.gpg
```

- Exportiere den öffentlichen Schlüssel einer bestimmten Email-Adresse nach STDOUT:

```bash
gpg2 --export --armor hans@beispiel.de
```

- Exportiere den privaten Schlüssel einer bestimmten Email-Adresse nach STDOUT:

```bash
gpg2 --export-secret-keys --armor hans@beispiel.de
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo, fdroid, fdroidcl, ffprobe, ffsend, fg, firefox, fortune, fuck, g++, gdb, gpg2, grep: add German translation (#5361) | 2021-03-07T15:12:23 | [621355ceaf12](https://github.com/tldr-pages/tldr/commit/621355ceaf120c12636ae359cdf108678acd89db)

