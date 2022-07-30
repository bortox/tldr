---
author: ['Noemi']
date: 1635772490
title: "todo"
description: "todo, Un semplice gestore per i todo da linea di comando."
categories: "common"
---
> Maggiori informazioni: <https://todoman.readthedocs.io>.

- Elenco dei task che possono essere inizializzati:

```bash
todo list --startable
```

- Aggiungere un nuovo task alla lista delle cose da fare per lavoro:

```bash
todo new cose_da_fare --list lavoro
```

- Aggiungere una località ad un task con un dato ID:

```bash
todo edit --location nome_località task_id
```

- Mostrare i dettagli di un task:

```bash
todo show task_id
```

- Contrassegnare un task con un ID specifico come completato:

```bash
todo done task_id1 task_id2 ...
```

- Eliminare un task:

```bash
todo delete task_id
```

- Eliminare un task completato e ripristinare gli ID dei task rimanenti:

```bash
todo flush
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Noemi](mailto:33022202+noemi3@users.noreply.github.com) | todo: add Italian translation (#7217) | 2021-11-01T14:14:50 | [4f7794c7a277](https://github.com/tldr-pages/tldr/commit/4f7794c7a27714a8a8d35d3fd9b49b312dc14ff4)

