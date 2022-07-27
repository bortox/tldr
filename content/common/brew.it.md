---
author: ['marchersimon']
date: 1631516812
title: "brew, TLDR Pages"
description: "brew, Gestore di pacchetti per macOS."
categories: "common"
---
> Maggiori informazioni: <https://brew.sh>.

- Cerca formule e cask:

```bash
brew search testo
```

- Installa l'ultima versione stabile di una formula (usa `--devel` per le versioni in sviluppo):

```bash
brew install formula
```

- Mostra tutte le formule installate:

```bash
brew list
```

- Mostra le formule installate che non sono dipendenze di un'altra formula installata:

```bash
brew leaves
```

- Aggiorna una formula installata (se non viene fornito il nome di nessuna formula, tutte le formule installate verranno aggiornate):

```bash
brew upgrade formula
```

- Trova la versione più aggiornata di Homebrew e di tutte le formule da GitHub:

```bash
brew update
```

- Mostra le informazioni su una specifica formula (versione, percorso di installazione, dipendenze, ecc...):

```bash
brew info formula
```

- Verifica se la versione installata di Homebrew presenta dei problemi:

```bash
brew doctor
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | brew*: move to common (#6507) | 2021-09-13T09:06:52 | [4fbb601f63ee](https://github.com/tldr-pages/tldr/commit/4fbb601f63ee14b0ed9a23d1d9c78bb102a23776)

