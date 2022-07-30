---
author: ['Daniel', 'marchersimon']
date: 1634914980
title: "brew bundle"
description: "brew bundle, Bundler für Homebrew, Homebrew Cask und den Mac App Store."
categories: "common"
---
> Weitere Informationen: <https://github.com/Homebrew/homebrew-bundle>.

- Installiere Pakete aus einer Brewfile im aktuellen Pfad:

```bash
brew bundle
```

- Installiere Pakete aus einer bestimmten Brewfile:

```bash
brew bundle --file=pfad/zu/brewfile
```

- Gib eine Liste mit allen installierten Paketen aus:

```bash
brew bundle dump
```

- Deinstalliere Pakete, die nicht in der Brewfile aufgelistet sind:

```bash
brew bundle cleanup --force
```

- Prüfe, ob von einem Paket die aktuellste Version installiert ist:

```bash
brew bundle check
```

- Zeige alle Pakete, die in der Brewfile aufgelistet sind:

```bash
brew bundle list --all
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | brew*: move to common (#6507) | 2021-09-13T09:06:52 | [4fbb601f63ee](https://github.com/tldr-pages/tldr/commit/4fbb601f63ee14b0ed9a23d1d9c78bb102a23776)

