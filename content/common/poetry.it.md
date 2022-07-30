---
author: ['Francesco Franchina']
date: 1635360802
title: "poetry"
description: "poetry, Gestore di pacchetti e dipendenze per Python."
categories: "common"
---
> Maggiori informazioni: <https://python-poetry.org/docs>.

- Crea un nuovo progetto Poetry nella cartella specificata:

```bash
poetry new nome_progetto
```

- Installa una dipendenza e le relative sottodipendenze:

```bash
poetry add dipendenza
```

- Inizializza interattivamente la nuova cartella come un nuovo progetto Poetry:

```bash
poetry init
```

- Recupera l'ultima versione di ciascuna dipendenza e aggiorna il file `poetry.lock`:

```bash
poetry update
```

- Esegue un comando all'interno dell'ambiente virtuale del progetto:

```bash
poetry run comando
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Francesco Franchina](mailto:cescus92@gmail.com) | black, flake8, poetry: add Italian translation | 2021-10-27T20:53:22 | [20035f807ad8](https://github.com/tldr-pages/tldr/commit/20035f807ad8f42aadad352e8818c975b3f4b7da)

