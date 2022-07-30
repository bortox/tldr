---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "choco source"
description: "choco source, Verwalte die Paketquellen mit Chocolatey."
categories: "windows"
---
> Weitere Informationen: <https://chocolatey.org/docs/commands-source>.

- Gib alle momentan verfügbaren Quellen aus:

```bash
choco source list
```

- Füge eine neue Paketquelle hinzu:

```bash
choco source add --name name --source url
```

- Füge eine neue Paketquelle mit Zugangsdaten hinzu:

```bash
choco source add --name name --source url --user benutzername --password passwort
```

- Füge eine neue Paketquelle mit Client-Zertifikat hinzu:

```bash
choco source add --name name --source url --cert pfad/zu/zertifikat
```

- Aktiviere eine Paketquelle:

```bash
choco source enable --name name
```

- Deaktiviere eine Paketquelle:

```bash
choco source disable --name name
```

- Entferne eine Paketquelle:

```bash
choco source remove --name name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[LukBukkit](mailto:luk.bukkit@gmail.com) | choco-source: add German translation | 2020-10-13T00:10:19 | [b86125fc2a5b](https://github.com/tldr-pages/tldr/commit/b86125fc2a5b2e8c2e936021c47249d8e0e59e7b)

