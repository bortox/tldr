---
author: ['Patrice Denis', 'Agno94']
date: 1618665963
title: "apt-mark, TLDR Pages"
description: "apt-mark, Servizio per cambiare lo stato di un pacchetto installato."
categories: "linux"
---
> Maggiori informazioni: <https://manpages.debian.org/latest/apt/apt-mark.8.html>.

- Contrassegna un pacchetto come installato automaticamente:

```bash
sudo apt-mark auto nome_del_pacchetto
```

- Mantiene un pacchetto alla sua versione attuale e ne previene l'aggiornamento:

```bash
sudo apt-mark hold nome_del_pacchetto
```

- Consente ad un pacchetto di essere nuovamente aggiornato:

```bash
sudo apt-mark unhold nome_del_pacchetto
```

- Mostra i pacchetti installati manualmente:

```bash
apt-mark showmanual
```

- Visualizza i pacchetti mantenuti alla versione attuale che non sono stati aggiornati:

```bash
apt-mark showhold
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Agno94](mailto:agnophi@gmail.com) | apt*, dpkg*: add Italian translation (#4854) | 2020-11-02T13:08:24 | [a722b14d8608](https://github.com/tldr-pages/tldr/commit/a722b14d86085d614175c300539e3ccd8b957a48)

