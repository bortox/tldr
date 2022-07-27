---
author: ['Stig124', 'Agno94']
date: 1625841955
title: "dpkg-query, TLDR Pages"
description: "dpkg-query, Uno strumento che mostra informazioni sui pacchetti installati."
categories: "linux"
---
> Maggiori informazioni: <https://manpages.debian.org/latest/dpkg/dpkg-query.1.html>.

- Elenca tutti i pacchetti installati:

```bash
dpkg-query -l
```

- Elenca i pacchetti installati con nomi che combaciano con una data espressione:

```bash
dpkg-query -l 'espressione_pattern'
```

- Elenca tutti i file installati da una pacchetto:

```bash
dpkg-query -L nome_del_pacchetto
```

- Mostra le informazioni riguardanti un pacchetto:

```bash
dpkg-query -s nome_del_pacchetto
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Agno94](mailto:agnophi@gmail.com) | apt*, dpkg*: add Italian translation (#4854) | 2020-11-02T13:08:24 | [a722b14d8608](https://github.com/tldr-pages/tldr/commit/a722b14d86085d614175c300539e3ccd8b957a48)

