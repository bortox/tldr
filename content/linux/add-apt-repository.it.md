---
author: ['Stig124', 'Agno94']
date: 1625841955
title: "add-apt-repository, TLDR Pages"
description: "add-apt-repository, Gestisce le definizioni di repository apt."
categories: "linux"
---
> Maggiori informazioni: <https://manned.org/apt-add-repository>.

- Aggiunge un nuovo repository apt:

```bash
add-apt-repository identificativo_del_repository
```

- Rimuove un repository apt:

```bash
add-apt-repository --remove identificativo_del_repository
```

- Aggiorna la cache dei pacchetti dopo aver aggiunto un repository:

```bash
add-apt-repository --update identificativo_del_repository
```

- Attiva i pacchetti sorgente:

```bash
add-apt-repository --enable-source identificativo_del_repository
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Agno94](mailto:agnophi@gmail.com) | apt*, dpkg*: add Italian translation (#4854) | 2020-11-02T13:08:24 | [a722b14d8608](https://github.com/tldr-pages/tldr/commit/a722b14d86085d614175c300539e3ccd8b957a48)

