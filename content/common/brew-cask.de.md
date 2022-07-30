---
author: ['S-Espinet']
date: 1635775257
title: "brew cask"
description: "brew cask, Paketmanager für macOS-Anwendungen, die als Binärdateien verteilt werden."
categories: "common"
---
> Weitere Informationen: <https://github.com/Homebrew/homebrew-cask>.

- Suche nach Formeln und Casks:

```bash
brew search text
```

- Installiere ein Cask:

```bash
brew cask install caskname
```

- Liste alle installierten Casks auf:

```bash
brew list --cask
```

- Liste installierte Casks auf, für die neuere Versionen verfügbar sind:

```bash
brew outdated --cask
```

- Aktualisiere ein installiertes Cask (wenn kein Caskname angegeben wird, werden alle installierten Casks aktualisiert):

```bash
brew upgrade --cask caskname
```

- Deinstalliere ein Cask

```bash
brew cask uninstall caskname
```

- Deinstalliere ein Cask und entferne zugehörige Einstellungen und Dateien:

```bash
brew upgrade --cask caskname
```

- Zeige informationen zu einem bestimmten Cask an:

```bash
brew cask uninstall caskname
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[S-Espinet](mailto:91517918+S-Espinet@users.noreply.github.com) | brew-cask: add German translation (#7331) | 2021-11-01T15:00:57 | [211bb41d8632](https://github.com/tldr-pages/tldr/commit/211bb41d86320341c3fa2f225941ef4db0ee96b9)

