---
author: ['Francesco Franchina']
date: 1635360802
title: "flake8"
description: "flake8, Programma per verificare lo stile e la qualità di un codice Python."
categories: "common"
---
> Maggiori informazioni: <https://flake8.pycqa.org/>.

- Analizza ricorsivamente un file o una cartella:

```bash
flake8 percorso/a/file_o_cartella
```

- Analizza ricorsivamente un file o una cartella e mostra le righe contenenti errori:

```bash
flake8 --show-source percorso/a/file_o_cartella
```

- Analizza ricorsivamente un file o una cartella e ignora la lista delle regole specificate. (La lista con tutte le regole è consultabile su flake8rules.com):

```bash
flake8 --ignore regola1,regola2 percorso/a/file_o_cartella
```

- Analizza ricorsivamente un file o una cartella ma esclude i file che corrispondono a una sottostringa o a un glob:

```bash
flake8 --exclude sottostringa1,glob2 percorso/a/file_o_cartella
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Francesco Franchina](mailto:cescus92@gmail.com) | black, flake8, poetry: add Italian translation | 2021-10-27T20:53:22 | [20035f807ad8](https://github.com/tldr-pages/tldr/commit/20035f807ad8f42aadad352e8818c975b3f4b7da)

