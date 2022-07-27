---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "choco-apikey, TLDR Pages"
description: "choco-apikey, Verwalte die API-Schlüssel für die Quellen von Chocolatey."
categories: "windows"
---
> Weitere Informationen: <https://chocolatey.org/docs/commands-apikey>.

- Gib eine Liste von Quellen und ihren API-Schlüsseln aus:

```bash
choco apikey
```

- Zeige eine bestimmte Quelle und ihren API-Schlüssel an:

```bash
choco apikey --source "quell_url"
```

- Setze den API-Schlüssel für eine Quelle:

```bash
choco apikey --source "quell_url" --key "api_schluessel"
```

- Entferne den API-Schlüssel einer Quelle:

```bash
choco apikey --source "quell_url" --remove
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[LukBukkit](mailto:luk.bukkit@gmail.com) | choco-apikey: add German translation | 2020-10-13T00:10:19 | [293ebe1cb578](https://github.com/tldr-pages/tldr/commit/293ebe1cb578803e9e5ca921bbee34134dba7884)

