---
author: ['Guido Lena Cota']
date: 1602386151
title: "git mv, TLDR Pages"
description: "git mv, Sposta o rinomina file e aggiorna l'indice Git."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-mv>.

- Sposta i file nella repository e aggiungi l'operazione al commit successivo:

```bash
git mv percorso/al/file nuovo/percorso/al/file
```

- Rinomina i file e aggiungi l'operazione al commit successivo:

```bash
git mv file file_rinominato
```

- Sposta sovrascrivendo eventuali file esistenti nel percorso di destinazione:

```bash
git mv --force percorso/al/file nuovo/percorso/al/file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git-mv: add it translation (#4520) | 2020-10-11T05:15:51 | [afe89f7a7fae](https://github.com/tldr-pages/tldr/commit/afe89f7a7fae303f81bd75231ff7effd45dd638e)

