---
author: ['marchersimon']
date: 1631516812
title: "brew bundle, TLDR Pages"
description: "brew bundle, Bundler per Homebrew, Homebrew Cask e per il Mac App Store."
categories: "common"
---
> Maggiori informazioni: <https://github.com/Homebrew/homebrew-bundle>.

- Installa un pacchetto da un Brewfile nel percorso corrente:

```bash
brew bundle
```

- Installa pacchetti da un Brewfile specifico in un percorso specifico:

```bash
brew bundle --file=percorso/del/file
```

- Crea un Brewfile con tutti i pacchetti installati:

```bash
brew bundle dump
```

- Disinstalla tutti i pacchetti non specificati nel Brewfile:

```bash
brew bundle cleanup --force
```

- Controlla se c'è qualcosa da installare o da aggiornare nel Brewfile:

```bash
brew bundle check
```

- Mostra una lista di tutte le righe presenti nel Brewfile:

```bash
brew bundle list --all
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | brew*: move to common (#6507) | 2021-09-13T09:06:52 | [4fbb601f63ee](https://github.com/tldr-pages/tldr/commit/4fbb601f63ee14b0ed9a23d1d9c78bb102a23776)

