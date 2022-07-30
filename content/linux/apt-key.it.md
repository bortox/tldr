---
author: ['Patrice Denis', 'Agno94']
date: 1618665963
title: "apt-key"
description: "apt-key, Servizio di gestione delle chiavi per il gestore di pacchetti APT su Debian ed Ubuntu."
categories: "linux"
---
> Maggiori informazioni: <https://manpages.debian.org/latest/apt/apt-key.8.html>.

- Elenca le chiavi fidate:

```bash
apt-key list
```

- Aggiunge una chiave al portachiavi delle chiavi fidate:

```bash
apt-key add file_chiave_pubblica.asc
```

- Elimina una chiave dal portachiavi delle chiavi fidate:

```bash
apt-key del id_chiave
```

- Aggiunge una chiave remota al portachiavi delle chiavi fidate:

```bash
wget -qO - https://indirizzo.tld/filename.key | apt-key add -
```

- Aggiunge una chiave da un server di chiavi con il solo id della chiave:

```bash
apt-key adv --keyserver pgp.mit.edu --recv ID_DELLA_CHIAVE
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Agno94](mailto:agnophi@gmail.com) | apt*, dpkg*: add Italian translation (#4854) | 2020-11-02T13:08:24 | [a722b14d8608](https://github.com/tldr-pages/tldr/commit/a722b14d86085d614175c300539e3ccd8b957a48)

