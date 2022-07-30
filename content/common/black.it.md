---
author: ['Francesco Franchina']
date: 1635360802
title: "black"
description: "black, Un formattatore automatico di codice Python."
categories: "common"
---
> Maggiori informazioni: <https://github.com/psf/black>.

- Auto-formatta un file o un'intera cartella:

```bash
black percorso/a/file_o_cartella
```

- Formatta il codice che gli viene passato come stringa:

```bash
black -c "codice"
```

- Mostra i cambiamenti che verrebbero applicati a ciascun file:

```bash
black --diff percorso/a/file_o_cartella
```

- Verifica se i file necessitano di auto-formattazione senza modificare nulla:

```bash
black --check percorso/a/file_o_cartella
```

- Auto-formatta un file o una cartella senza produrre output:

```bash
black --quiet percorso/a/file_o_cartella
```

- Auto-formatta un file o una cartella senza sostituire gli apici con le doppie virgolette:

```bash
black --skip-string-normalization percorso/a/file_o_cartella
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Francesco Franchina](mailto:cescus92@gmail.com) | black, flake8, poetry: add Italian translation | 2021-10-27T20:53:22 | [20035f807ad8](https://github.com/tldr-pages/tldr/commit/20035f807ad8f42aadad352e8818c975b3f4b7da)

