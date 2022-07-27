---
author: ['Agno94', 'Patrice Denis', 'bl-ue']
date: 1618665963
title: "apt-get, TLDR Pages"
description: "apt-get, Servizio di gestione dei pacchetti per Debian e Ubuntu."
categories: "linux"
---
> Cerca i pacchetti usando `apt-cache`.

> Maggiori informazioni: <https://manpages.debian.org/latest/apt/apt-get.8.html>.

- Aggiorna la lista dei pacchetti e delle loro versioni disponibili (è consigliato eseguire questo comando prima di altri comandi `apt-get`):

```bash
apt-get update
```

- Installa un pacchetto, o lo aggiorna all'ultima versione disponibile:

```bash
apt-get install pacchetto
```

- Rimuove un pacchetto:

```bash
apt-get remove pacchetto
```

- Rimuove un pacchetto ed i suoi file di configurazione:

```bash
apt-get purge pacchetto
```

- Aggiorna tutti i pacchetti installati alla versione disponibile più recente:

```bash
apt-get upgrade
```

- Pulisce gli archivi locali - rimuovendo i file (.deb) da scaricamenti interrotti che non possono più essere scaricati:

```bash
apt-get autoclean
```

- Rimuove tutti i pacchetti che non sono più necessari:

```bash
apt-get autoremove
```

- Aggiorna tutti i pacchetti installati (come `upgrade`), rimuovendo i pacchetti obsoleti ed installando ulteriori pacchetti per soddisfare le nuove dipendenze:

```bash
apt-get dist-upgrade
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Italian pages: fix (valid) tldr-lint errors (#5366) | 2021-03-08T20:39:35 | [527ea3cfa34f](https://github.com/tldr-pages/tldr/commit/527ea3cfa34f69c592a56fef273ed44286c61f06)
[Agno94](mailto:agnophi@gmail.com) | apt*, dpkg*: add Italian translation (#4854) | 2020-11-02T13:08:24 | [a722b14d8608](https://github.com/tldr-pages/tldr/commit/a722b14d86085d614175c300539e3ccd8b957a48)

