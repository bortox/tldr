---
author: ['Schneider', 'Lucas Gabriel Schneider', 'Marco Bonelli']
date: 1612112718
title: "borg"
description: "borg, Strumento di backup con deduplicazione."
categories: "common"
---
> Crea backup locali o remoti che sono montabili come filesystem.

> Maggiori informazioni: <https://borgbackup.readthedocs.io/en/stable/usage/general.html>.

- Inizializza una repository (locale):

```bash
borg init /percorso/a/repo_o_directory
```

- Esegui il backup di una directory nella repository, creando un archivio chiamato "Lunedi":

```bash
borg create --progress /percorso/a/repo_o_directory::Lunedi /percorso/a/directory_sorgente
```

- Lista tutti gli archivi in una repository:

```bash
borg list /percorso/a/repo_o_directory
```

- Estrai una specifica directory dall'archivio "Lunedi" in una repository remota, escludendo tutti i file `.ext`:

```bash
borg extract utente@host:/percorso/a/repo_o_directory::Lunedi percorso/a/cartella_destinazione --exclude '*.ext'
```

- Riduci una repository eliminando tutti gli archivi più vecchi di 7 giorni, elencando i cambiamenti:

```bash
borg prune --keep-within 7d --list /percorso/a/repo_o_directory
```

- Monta una repository come filesystem FUSE:

```bash
borg mount /percorso/a/repo_o_directory::Lunedi /percorso/a/mountpoint
```

- Mostra aiuto sul come creare archivi:

```bash
borg create --help
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\borg.md: add homepage | 2019-05-14T19:40:23 | [4d82b28eadb2](https://github.com/tldr-pages/tldr/commit/4d82b28eadb2d8a504b3a4412fb2056d9a5ecca8)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | borg: add Italian translation. | 2019-01-28T19:10:19 | [c2351ef4ec97](https://github.com/tldr-pages/tldr/commit/c2351ef4ec9727812fe39eeb8409f388cab6c75f)

