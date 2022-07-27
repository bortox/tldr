---
author: ['Leandro Meleti']
date: 1633356098
title: "apk, TLDR Pages"
description: "apk, Alpine Linux-Paketverwaltungstool."
categories: "linux"
---
> Weitere Informationen: <https://wiki.alpinelinux.org/wiki/Alpine_Linux_package_management>.

- Aktualisiere die Indizes von allen externen Repositories:

```bash
apk update
```

- Installiere ein neues Paket:

```bash
apk add paket
```

- Entferne ein Paket:

```bash
apk del paket
```

- Repariere oder aktualisiere ein Paket, ohne die Hauptabhängigkeiten zu ändern:

```bash
apk fix paket
```

- Suche Pakete mit einem Schlüsselwort:

```bash
apk search schlüsselwort
```

- Erhalte Informationen über ein bestimmtes Paket:

```bash
apk info paket
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Leandro Meleti](mailto:leandromeleti97@hotmail.com) | apk: add German translation (#6771) | 2021-10-04T16:01:38 | [d3b4517498f3](https://github.com/tldr-pages/tldr/commit/d3b4517498f328f9b99a0c02bf5f9453bae3092b)

