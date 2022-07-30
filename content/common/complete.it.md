---
author: ['Marco Bonelli', 'marchersimon']
date: 1618756407
title: "complete"
description: "complete, Fornisce autocompletamento per argomenti dei comandi della shell."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/bash/manual/html_node/Programmable-Completion-Builtins.html>.

- Applica ad un comando una funzione per gestirne l'autocompletamento:

```bash
complete -F funzione comando
```

- Applica ad un comando un altro comando per gestirne l'autocompletamento:

```bash
complete -C comando_per_autocompletamento comando
```

- Applica l'autocompletamento senza aggiungere uno spazio dopo la parola completata:

```bash
complete -o nospace -F function comando
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | complete: add link | 2021-04-18T16:33:27 | [02f8ccffbede](https://github.com/tldr-pages/tldr/commit/02f8ccffbede5fe1feac284569e1f8a9ee917e09)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | complete: add Italian translation. | 2019-06-10T01:35:02 | [d90196e7ece8](https://github.com/tldr-pages/tldr/commit/d90196e7ece84c2ca5e0ac92ef47879082fb53be)

