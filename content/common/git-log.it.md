---
author: ['Guido Lena Cota', 'Muhammad Falak R Wani']
date: 1635631367
title: "git log, TLDR Pages"
description: "git log, Mostra la cronologia dei commit."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-log>.

- Mostra la sequenza dei commit del ramo del repository in uso, a partire dal commit corrente e andando in ordine cronologico inverso:

```bash
git log
```

- Mostra la cronologia di un dato file o cartella, mostrando anche le modifiche:

```bash
git log -p percorso/al/file_o_directory
```

- Offri una panoramica dei file che sono cambiati ad ogni commit:

```bash
git log --stat
```

- Mostra il grafo dei commit nel ramo corrente, includendo solo la prima riga di ogni messaggio di commit:

```bash
git log --oneline --graph
```

- Mostra il grafo di tutti i commit, tag e rami dell'intero repository:

```bash
git log --oneline --decorate --all --graph
```

- Mostra solo i commit il cui messaggio contiene una data stringa (ignorando maiuscole/minuscole):

```bash
git log -i --grep stringa_da_cercare
```

- Mostra gli ultimi N commit di un certo autore:

```bash
git log -n numero --author=autore
```

- Mostra i commit effettuati tra due date (yyyy-mm-dd):

```bash
git log --before="2017-01-29" --after="2017-01-17"
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | git-log: clarify date format with example (#7150) | 2021-10-31T00:02:47 | [11f811cc994d](https://github.com/tldr-pages/tldr/commit/11f811cc994ddea4ff4dd07d254b0da120d2dc18)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4627) * git-archive: add italian translation * git-bundle: add italian translation * git-cat-file: add [...] | 2020-10-11T05:46:17 | [b1a891a34a7a](https://github.com/tldr-pages/tldr/commit/b1a891a34a7a1d75b7b11fea3d9c3206713822f7)

