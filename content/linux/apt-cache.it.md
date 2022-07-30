---
author: ['Patrice Denis', 'Agno94']
date: 1618665963
title: "apt-cache"
description: "apt-cache, Strumenti di Debian e Ubuntu per richiedere informazioni sui pacchetti."
categories: "linux"
---
> Maggiori informazioni: <https://manpages.debian.org/latest/apt/apt-cache.8.html>.

- Cerca un pacchetto nelle sorgenti attuali:

```bash
apt-cache search query
```

- Mostra informazioni su un pacchetto:

```bash
apt-cache show pacchetto
```

- Mostra se un pacchetto è installato ed aggiornato:

```bash
apt-cache policy pacchetto
```

- Mostra le dipendenze di un pacchetto:

```bash
apt-cache depends pacchetto
```

- Mostra i pacchetti che dipendono da un particolare pacchetto:

```bash
apt-cache rdepends pacchetto
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Agno94](mailto:agnophi@gmail.com) | apt*, dpkg*: add Italian translation (#4854) | 2020-11-02T13:08:24 | [a722b14d8608](https://github.com/tldr-pages/tldr/commit/a722b14d86085d614175c300539e3ccd8b957a48)

