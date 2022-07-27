---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "choco new, TLDR Pages"
description: "choco new, Erstelle neue Paket-Beschreibungs-Dateien mit Chocolatey."
categories: "windows"
---
> Weitere Informationen: <https://chocolatey.org/docs/commands-new>.

- Erstelle ein neues Grundgerüst für ein Paket:

```bash
choco new paket_name
```

- Erstelle ein neues Paket mit einer bestimmten Version:

```bash
choco new paket_name --version version
```

- Erstelle ein neues Paket mit einem bestimmten Betreuer*innen-Namen:

```bash
choco new paket_name --maintainer betreuer*innen_name
```

- Erstelle ein neues Paket in einem bestimmten Ausgabe-Verzeichnis:

```bash
choco new paket_name --output-directory pfad/zu/verzeichnis
```

- Erstelle ein neues Paket mit verschiedenen URLs für die 32-Bit und 64-Bit Installationsroutinen:

```bash
choco new paket_name url="url" url64="url"
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[LukBukkit](mailto:luk.bukkit@gmail.com) | choco-new: add German translation | 2020-10-13T00:10:19 | [f5f30886f342](https://github.com/tldr-pages/tldr/commit/f5f30886f342b2d8f48b2e3bf4bfb6cee8d4fa46)

