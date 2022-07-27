---
author: ['Patrice Denis', 'Agno94']
date: 1618665963
title: "apt-add-repository, TLDR Pages"
description: "apt-add-repository, Gestisce le definizioni di repository apt."
categories: "linux"
---
> Maggiori informazioni: <https://manpages.debian.org/latest/software-properties-common/apt-add-repository.1.html>.

- Aggiunge un nuovo repository apt:

```bash
apt-add-repository identificativo_del_repository
```

- Rimuove un repository apt:

```bash
apt-add-repository --remove identificativo_del_repository
```

- Aggiorna la cache dei pacchetti dopo aver aggiunto un repository:

```bash
apt-add-repository --update identificativo_del_repository
```

- Attiva i pacchetti sorgente:

```bash
apt-add-repository --enable-source identificativo_del_repository
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Agno94](mailto:agnophi@gmail.com) | apt*, dpkg*: add Italian translation (#4854) | 2020-11-02T13:08:24 | [a722b14d8608](https://github.com/tldr-pages/tldr/commit/a722b14d86085d614175c300539e3ccd8b957a48)

