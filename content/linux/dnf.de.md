---
author: ['pixel', 'FantasyCookie17', 'MarkusS', 'marchersimon']
date: 1632941775
title: "dnf, TLDR Pages"
description: "dnf, Paketmanagement Tool für RHEL, Fedora, und CentOS (ersetzt yum)."
categories: "linux"
---
> Weitere Informationen: <https://dnf.readthedocs.io>.

- Aktualisiere alle Pakete auf die neueste Version:

```bash
sudo dnf upgrade
```

- Suche nach Paketen:

```bash
dnf search schlüsselwort
```

- Zeige Daten über ein bestimmtes Paket an:

```bash
dnf info paket
```

- Installiere ein neues Paket:

```bash
sudo dnf install paket
```

- Installiere ein neues Paket und antworte "ja" auf alle Fragen:

```bash
sudo dnf -y install paket
```

- Entferne ein Paket:

```bash
sudo dnf remove paket
```

- Liste alle Pakete auf:

```bash
dnf list --installed
```

- Zeige welches Paket eine Datei besitzt:

```bash
dnf provides pfad/zu/datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | *: normalize readthedocs.io more information links (#6593) | 2021-09-29T20:56:15 | [d22ca9676f6c](https://github.com/tldr-pages/tldr/commit/d22ca9676f6c02b19e6e1728f5ea777e7985c9d0)
[FantasyCookie17](mailto:fantasycookie17@artemislena.eu) | German pages: Change 'neuste' to 'neueste' (#5844) | 2021-04-28T10:57:14 | [48b7458c8559](https://github.com/tldr-pages/tldr/commit/48b7458c85594857653369e5e9941fe3961c79f0)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[MarkusS](mailto:markusscoding@outlook.com) | alpine, apt*, dnf, ip*: add German translation (#4707) | 2020-10-19T18:41:28 | [6e04e6dfc57e](https://github.com/tldr-pages/tldr/commit/6e04e6dfc57e323fed7b4ab2e5f46358463b2008)

