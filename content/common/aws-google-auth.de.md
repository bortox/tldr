---
author: ['Felix Brilej', 'bl-ue', 'marchersimon']
date: 1619262596
title: "aws-google-auth, TLDR Pages"
description: "aws-google-auth, CLI, um temporäre AWS credentials (STS) über Google Apps als Single Sign-On Dienstleister zu erhalten."
categories: "common"
---
> Weitere Informationen: <https://github.com/cevoaustralia/aws-google-auth>.

- Einloggen mit Google SSO über IDP- und SP-Kennung für die Dauer einer Stunde:

```bash
aws-google-auth -u beispiel@beispiel.com -I $GOOGLE_IDP_ID -S $GOOGLE_SP_ID -d 3600
```

- Einloggen mit der Option eine Rolle auszuwählen (im Falle mehrerer verfügbarer SAML Rollen):

```bash
aws-google-auth -u beispiel@beispiel.com -I $GOOGLE_IDP_ID -S $GOOGLE_SP_ID -d 3600 -a
```

- Löse Aliasse von AWS Accounts auf:

```bash
aws-google-auth -u beispiel@beispiel.com -I $GOOGLE_IDP_ID -S $GOOGLE_SP_ID -d 3600 -a --resolve-aliases
```

- Zeige Hilfs-Informationen:

```bash
aws-google-auth -h
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | aws*: add German translation (#4827) | 2020-10-24T15:27:02 | [455f988c81a2](https://github.com/tldr-pages/tldr/commit/455f988c81a21f9d47983d5b1607d3d03b216db4)

