---
author: ['MeerBiene', 'lincc']
date: 1643487459
title: "acpi"
description: "acpi, Zeigt den Akkustatus oder Temperatur-Informationen an."
categories: "linux"
---
> Weitere Informationen: <https://sourceforge.net/projects/acpiclient/files/acpiclient/>.

- Zeige Informationen über den Akku an:

```bash
acpi
```

- Zeige Informationen zur Temperatur an:

```bash
acpi -t
```

- Zeige Informationen über die Kühlung an:

```bash
acpi -c
```

- Zeige Temperatur-Informationen in Fahrenheit an:

```bash
acpi -tf
```

- Zeige alle Informationen an:

```bash
acpi -V
```

- Extrahiere Informationen von `/proc`, anstatt von `/sys`:

```bash
acpi -p
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

