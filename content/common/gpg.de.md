---
author: ['b3nj4m1n', 'Lucas Gabriel Schneider', 'marchersimon', 'Daniel']
date: 1634914980
title: "gpg, TLDR Pages"
description: "gpg, GNU Privacy Guard."
categories: "common"
---
> Siehe `gpg2` für GNU Privacy Guard 2.

> Weitere Informationen: <https://gnupg.org>.

- Erstelle einen öffentlichen und privaten GPG Schlüssel interaktiv:

```bash
gpg --full-generate-key
```

- Signiere `doc.txt` ohne Verschlüsselung (Ausabe nach `doc.txt.asc`):

```bash
gpg --clearsign doc.txt
```

- Verschlüssle `doc.txt` für alice@beispiel.de (Ausgabe nach `doc.txt.gpg`):

```bash
gpg --encrypt --recipient alice@beispiel.de doc.txt
```

- Verschlüssle `doc.txt` nur mit Passwort (Ausgabe nach `doc.txt.gpg`):

```bash
gpg --symmetric doc.txt
```

- Entschlüssle `doc.txt.gpg` (Ausgabe nach stdout):

```bash
gpg --decrypt doc.txt.gpg
```

- Importiere einen öffentlichen Schlüssel:

```bash
gpg --import schlüssel.gpg
```

- Exportiere den öffentlichen Schlüssel von alice@beispiel.de (Ausgabe nach stdout):

```bash
gpg --export --armor alice@beispiel.de
```

- Exportiere den privaten Schlüssel von alice@beispiel.de (Ausgabe nach stdout):

```bash
gpg --export-secret-keys --armor alice@beispiel.de
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, ansible-galaxy, convert, dd, exa, fuck, git-*, gpg, ls, mv: sync German page (#6226) | 2021-07-18T20:00:45 | [1dcdac60df90](https://github.com/tldr-pages/tldr/commit/1dcdac60df901488a051d3f2f2e4171a158be904)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[b3nj4m1n](mailto:b3nj4m1n@gmx.net) | gpg: add German translation | 2020-07-02T17:41:08 | [34a36465bf55](https://github.com/tldr-pages/tldr/commit/34a36465bf5523511f6a36ddeb739e4bc0964ae7)

