---
author: ['bl-ue', 'Felix Brilej', 'Daniel', 'marchersimon']
date: 1634914980
title: "aws ec2"
description: "aws ec2, CLI für AWS EC2."
categories: "common"
---
> AWS EC2 stellt eine sichere und skalierbare Einheit in der AWS Cloud zur Verfügung, um ein schnelleres Entwickeln und Ausrollen von Software zu ermöglichen.

> Weitere Informationen: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/ec2/index.html>.

- Liste alle verfügbaren EC2 Befehle auf:

```bash
aws ec2 help
```

- Zeige Hilfe für bestimmte EC2 Unterbefehle an:

```bash
aws ec2 unterbefehl help
```

- Liste Informationen zu einer bestimmten Instanz auf:

```bash
aws ec2 describe-instances --instance-ids instanz_id
```

- Liste Informationen zu allen Instanzen auf:

```bash
aws ec2 describe-instances
```

- Liste Informationen zu allen EC2 Volumen auf:

```bash
aws ec2 describe-volumes
```

- Liste Informationen zu einem bestimmten EC2 Volumen auf:

```bash
aws ec2 describe-volume --volume-id volumen_id
```

- Erstelle einen Snapshot, basierend auf einem EC2 Volumen:

```bash
aws ec2 create-snapshot --volume-id volumen_id
```

- Liste alle verfügbaren AMIs (Amazon Machine Images) auf:

```bash
aws ec2 describe-images
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | aws*: add German translation (#4827) | 2020-10-24T15:27:02 | [455f988c81a2](https://github.com/tldr-pages/tldr/commit/455f988c81a21f9d47983d5b1607d3d03b216db4)

