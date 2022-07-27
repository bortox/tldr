---
author: ['Felix Brilej', 'bl-ue', 'marchersimon', 'Daniel']
date: 1634914980
title: "aws, TLDR Pages"
description: "aws, Das offizielle CLI für Amazon Web Services."
categories: "common"
---
> Manche Unterbefehle wie `aws s3` sind separat dokumentiert.

> Weitere Informationen: <https://aws.amazon.com/cli>.

- Konfiguriere die AWS Kommandozeile:

```bash
aws configure wizard
```

- Konfiguriere die AWS Kommandozeile mithilfe von SSO:

```bash
aws configure sso
```

- Zeige Hilfe für ein Kommando an:

```bash
aws befehl help
```

- Zeige Informationen über die eigene angenomme Identität (häufig benutzt zur Fehlersuche):

```bash
aws sts get-caller-identity
```

- Liste alle AWS Ressourcen in einer Region mit YAML Formatierung auf:

```bash
aws dynamodb list-tables --region us-east-1 --output yaml
```

- Erstelle einen IAM Benutzer mit Ausführungsassistent:

```bash
aws iam create-user --cli-auto-prompt
```

- Öffne einen Assitenten für eine AWS Ressource:

```bash
aws dynamodb wizard neue_tabelle
```

- Erstelle einen JSON CLI-Aufbau (hilfreich für Infrastruktur-Automation):

```bash
aws dynamodb update-table --generate-cli-skeleton
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | aws*: add German translation (#4827) | 2020-10-24T15:27:02 | [455f988c81a2](https://github.com/tldr-pages/tldr/commit/455f988c81a21f9d47983d5b1607d3d03b216db4)

