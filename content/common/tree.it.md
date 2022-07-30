---
author: ['marchersimon']
date: 1632060820
title: "tree"
description: "tree, Mostra i contenuti della cartella corrente come un albero."
categories: "common"
---
> Maggiori informazioni: <http://mama.indstate.edu/users/ice/tree/>.

- Stampa file e cartella fino al 'num'-esimo livello di profondità (dove 1 significa la cartella corrente):

```bash
tree -L num
```

- Stampa solamente le cartelle:

```bash
tree -d
```

- Stampa anche i file nascosti con la colorazione attiva:

```bash
tree -a -C
```

- Stampa l'albero senza linee di indentazione, mostrando invece il percorso completo (usa `-N` per non convertire caratteri non stampabili in sequenze di escape):

```bash
tree -i -f
```

- Stampa la dimensione di ogni file e la dimensione totale di ogni cartella, in formato leggibile dall'utente:

```bash
tree -s -h --du
```

- Stampa i file all'interno dell'albero gerarchico, utilizzando espressioni di metacaratteri (glob pattern) per escludere le cartelle che non contengono file corrispondenti alla ricerca:

```bash
tree -P '*.txt' --prune
```

- Stampa le cartelle all'interno dell'albero gerarchico, utilizzando espressioni di metacaratteri (glob pattern) per escludere le cartelle che non sono progenitori di quelle desiderate:

```bash
tree -P nomi_di_cartelle --matchdirs --prune
```

- Stampa l'albero ignorando le cartelle date:

```bash
tree -I 'nome_cartella1|nome_cartella2'
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pwgen, sshuttle, trap, tree: move to common (#6551) | 2021-09-19T16:13:40 | [6474a3284244](https://github.com/tldr-pages/tldr/commit/6474a3284244a623c5ba32264a99d6a27a3bcce3)

