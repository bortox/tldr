---
author: ['Patrice Denis', 'Agno94', 'Reinhart Previano Koentjoro']
date: 1641608133
title: "apt"
description: "apt, Servizio di gestione dei pacchetti per distribuzioni basate su Debian."
categories: "linux"
---
> Rimpiazzo raccomandato di `apt-get` quando usato interattivamente su Ubuntu 16.04 e versioni successive.

> Maggiori informazioni: <https://manpages.debian.org/latest/apt/apt.8.html>.

- Aggiorna la lista dei pacchetti e delle loro versioni disponibili (è consigliato eseguire questo comando prima di altri comandi `apt`):

```bash
sudo apt update
```

- Cerca per un dato pacchetto:

```bash
apt search pacchetto
```

- Mostra le informazioni su un pacchetto:

```bash
apt show pacchetto
```

- Installa un pacchetto, o lo aggiorna all'ultima versione disponibile:

```bash
sudo apt install pacchetto
```

- Rimuove un pacchetto (usando `purge` rimuove anche i suoi file di configurazione):

```bash
sudo apt remove pacchetto
```

- Aggiorna tutti i pacchetti installati alla versione disponibile più recente:

```bash
sudo apt upgrade
```

- Elenca tutti i pacchetti:

```bash
apt list
```

- Elenca i pacchetti installati:

```bash
apt list --installed
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | apt: add backticks to apt-get (#7620) | 2022-01-08T03:15:33 | [e97d77689ab9](https://github.com/tldr-pages/tldr/commit/e97d77689ab99cfb2860768a9a50a0a65a4e03bd)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Agno94](mailto:agnophi@gmail.com) | apt*, dpkg*: add Italian translation (#4854) | 2020-11-02T13:08:24 | [a722b14d8608](https://github.com/tldr-pages/tldr/commit/a722b14d86085d614175c300539e3ccd8b957a48)

