---
author: ['Plato', 'Guido Lena Cota']
date: 1602536890
title: "git bundle"
description: "git bundle, Colloca oggetti e riferimenti in un archivio."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-bundle>.

- Crea un file bundle che contiene tutti gli oggetti e riferimenti di un dato ramo:

```bash
git bundle create percorso/al/file.bundle nome_ramo
```

- Crea un file bundle di tutti i rami:

```bash
git bundle create percorso/al/file.bundle --all
```

- Crea un file bundle degli ultimi 5 commit sul ramo corrente:

```bash
git bundle create percorso/al/file.bundle -5 HEAD
```

- Crea un file bundle degli ultimi 7 giorni:

```bash
git bundle create percorso/al/file.bundle --since=7.days HEAD
```

- Verifica che un file bundle sia valido e possa essere applicato al repository in uso:

```bash
git bundle verify percorso/al/file.bundle
```

- Stampa su standard output la lista di riferimenti contenuti in un bundle:

```bash
git bundle unbundle percorso/al/file.bundle
```

- Dato un file bundle, estrai un ramo specifico nel repository in uso:

```bash
git pull percorso/al/file.bundle nome_ramo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Plato](mailto:platoo@outlook.it) | git-bundle: fix typo in Italian translation (#4630) | 2020-10-12T23:08:10 | [9f3f131a8ead](https://github.com/tldr-pages/tldr/commit/9f3f131a8eade0dd0404a647ab563643272b3c35)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4627) * git-archive: add italian translation * git-bundle: add italian translation * git-cat-file: add [...] | 2020-10-11T05:46:17 | [b1a891a34a7a](https://github.com/tldr-pages/tldr/commit/b1a891a34a7a1d75b7b11fea3d9c3206713822f7)

