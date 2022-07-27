---
author: ['Marco Bonelli']
date: 1570281951
title: "erl, TLDR Pages"
description: "erl, Esegui e gestisci programmi nel linguaggio di programmazione Erlang."
categories: "common"
---
> Maggiori informazioni: <https://www.erlang.org>.

- Compila ed esegui un programma Erlang sequenziale come un comune script e poi esci:

```bash
erlc file && erl -noshell 'modulo:funzione(argomenti), init:stop().'
```

- Connetti ad un nodo Erlang in esecuzione:

```bash
erl -remsh nome_nodo@hostname -sname soprannome -hidden -setcookie cookie_nodo_remoto
```

- Fai caricare alla shell Erlang dei moduli da una directory:

```bash
erl -pa cartella_con_file_beam
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | erl: add Italian translation. | 2019-10-05T15:25:51 | [6aabf8d613ae](https://github.com/tldr-pages/tldr/commit/6aabf8d613ae8259db9f9fbe03e255e84a9b61e8)

