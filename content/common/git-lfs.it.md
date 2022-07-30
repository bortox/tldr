---
author: ['Guido Lena Cota']
date: 1602387977
title: "git lfs"
description: "git lfs, Lavora con file di grandi dimensioni in repository Git."
categories: "common"
---
> Maggiori informazioni: <https://git-lfs.github.com>.

- Inizializza Git LFS:

```bash
git lfs install
```

- Tieni traccia dei file che soddisfano un criterio glob:

```bash
git lfs track '*.bin'
```

- Cambia l'URL endpoint di Git LFS (utile quando server LFS e server Git sono separati):

```bash
git config -f .lfsconfig lfs.url lfs_url_endpoint
```

- Elenca i criteri tracciati:

```bash
git lfs track
```

- Elenca i file tracciati che sono già stati salvati in un commit:

```bash
git lfs ls-files
```

- Invia tutti gli oggetti Git LFS al server remoto (utile in caso di errori):

```bash
git lfs push --all nome_repository_remoto nome_ramo
```

- Scarica tutti gli oggetti Git LFS:

```bash
git lfs fetch
```

- Ripristina gli oggetti Git LFS:

```bash
git lfs checkout
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4627) * git-archive: add italian translation * git-bundle: add italian translation * git-cat-file: add [...] | 2020-10-11T05:46:17 | [b1a891a34a7a](https://github.com/tldr-pages/tldr/commit/b1a891a34a7a1d75b7b11fea3d9c3206713822f7)

