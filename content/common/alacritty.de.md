---
author: ['bl-ue', 'marchersimon']
date: 1621541621
title: "alacritty"
description: "alacritty, Plattformübergreifender, GPU-beschleunigter Terminalemulator."
categories: "common"
---
> Weitere Informationen: <https://github.com/alacritty/alacritty>.

- Öffne ein neues Alacritty-Fenster:

```bash
alacritty
```

- Starte Alacritty in einem bestimmten Arbeitsverzeichnis:

```bash
alacritty --working-directory pfad/zu/verzeichnis
```

- Führe einen Befehl in einem neuen Alacritty-Fenster aus:

```bash
alacritty -e befehl
```

- Gib eine alternative Konfigurations-Datei an (ist standardmäßig `$XDG_CONFIG_HOME/alacritty/alacritty.yml`):

```bash
alacritty --config-file pfad/zu/konfiguration.yml
```

- Starte mit aktiviertem Live-Konfigurations-Neuladen (kann auch standardmäßig in `alacritty.yml` eingestellt werden):

```bash
alacritty --live-config-reload --config-file pfad/zu/konfiguration.yml
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)

