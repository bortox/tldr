---
author: ['marchersimon']
date: 1631516812
title: "brew cask"
description: "brew cask, Gestore di pacchetti per applicazioni macOS distribuite sotto forma di file binari."
categories: "common"
---
> Maggiori informazioni: <https://github.com/Homebrew/homebrew-cask>.

- Cerca formule e cask:

```bash
brew search testo
```

- Installa un cask:

```bash
brew cask install nome_del_cask
```

- Elenca tutti i cask installati:

```bash
brew cask list
```

- Elenca i cask installati con versioni più nuove disponibili:

```bash
brew cask outdated
```

- Aggiorna un cask installato (se non viene fornito il nome di nessun cask, tutti i cask saranno aggiornati):

```bash
brew cask upgrade nome_del_cask
```

- Disinstalla un cask:

```bash
brew cask uninstall nome_del_cask
```

- Disinstalla un cask e rimuovi i relativi file e impostazioni:

```bash
brew cask zap nome_del_cask
```

- Mostra informazioni su uno specifico cask:

```bash
brew cask info nome_del_cask
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | brew*: move to common (#6507) | 2021-09-13T09:06:52 | [4fbb601f63ee](https://github.com/tldr-pages/tldr/commit/4fbb601f63ee14b0ed9a23d1d9c78bb102a23776)

