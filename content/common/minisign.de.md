---
author: ['FantasyCookie17', 'marchersimon', 'Daniel']
date: 1634914980
title: "minisign, TLDR Pages"
description: "minisign, Ein denkbar einfaches Werkzeug, um Dateien zu signieren und Signaturen zu verifizieren."
categories: "common"
---
> Weitere Informationen: <https://jedisct1.github.io/minisign/>.

- Generiere ein neues Schlüsselpaar im Standardpfad:

```bash
minisign -G
```

- Signiere eine Datei:

```bash
minisign -Sm pfad/zu/datei
```

- Signiere eine Datei und füge dabei einen vertrauenswürdigen (signierten) und einen nicht vertrauenswürdigen (unsignierten) Kommentar in der Signatur an:

```bash
minisign -Sm pfad/zu/datei -c "Nicht vertrauenswürdiger Kommentar" -t "Vertrauenswürdiger Kommentar"
```

- Verifiziere eine Datei und die vertrauenswürdigen Kommentare in ihrer Signatur gegen die angegebene Datei mit dem öffentlichen Schlüssel:

```bash
minisign -Vm pfad/zu/datei -p pfad/zu/öffentlicher_schlüssel.pub
```

- Verifiziere eine Datei und die vertrauenswürdigen Kommentare in ihrer Signatur gegen den angegebenen, in Base64 codierten öffentlichen Schlüssel:

```bash
minisign -Vm pfad/zu/datei -P "öffentlicher_schlüssel_base64"
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[FantasyCookie17](mailto:fantasycookie17@artemislena.eu) | minisign: add English and German pages (#5757) * Added English and German pages for Minisign * Fixed typo * Fixed the remaining typos [...] | 2021-04-18T16:20:17 | [7cc074d4d5bd](https://github.com/tldr-pages/tldr/commit/7cc074d4d5bd336ed4712727069308839a30c2e3)

