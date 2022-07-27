---
author: ['Felix Brilej', 'bl-ue', 'marchersimon', 'Daniel']
date: 1634914980
title: "aws-vault, TLDR Pages"
description: "aws-vault, Ein Tresor für Entwicklungsumgebungen, um AWS Sicherheitsschlüssel sicher speichern und abrufen zu können."
categories: "common"
---
> Weitere Informationen: <https://github.com/99designs/aws-vault>.

- Füge einen Sicherheitsschlüssel als Profil zu einem Tresor hinzu:

```bash
aws-vault add profil
```

- Führe einen Befehl mit AWS Sicherheitsschlüsseln aus dem angegebenen Profil aus:

```bash
aws-vault exec profil -- aws s3 ls
```

- Öffne ein Browserfenster für den Login in die AWS Konsole:

```bash
aws-vault login profil
```

- Liste alle Profile zusammen mit deren Sicherheitsschlüsseln und Sitzungen auf:

```bash
aws-vault list
```

- Rotiere die AWS Sicherheitsschlüssel für ein Profil:

```bash
aws-vault rotate profil
```

- Entferne Sicherheitsschlüsseln eines Profils aus dem Tresor:

```bash
aws-vault remove profil
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | aws*: add German translation (#4827) | 2020-10-24T15:27:02 | [455f988c81a2](https://github.com/tldr-pages/tldr/commit/455f988c81a21f9d47983d5b1607d3d03b216db4)

