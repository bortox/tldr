---
author: ['Axel Navarro', 'Agno94']
date: 1641649180
title: "dpkg-deb"
description: "dpkg-deb, Impacchetta, spacchetta e fornisce informazioni su archivi Debian."
categories: "linux"
---
> Maggiori informazioni: <https://manpages.debian.org/latest/dpkg/dpkg-deb.html>.

- Mostra le informazioni riguardo ad un pacchetto:

```bash
dpkg-deb --info percorso/al/file.deb
```

- Mostra il nome e la versione del pacchetto in una singola riga:

```bash
dpkg-deb --show percorso/al/file.deb
```

- Elenca i contenuti del pacchetto:

```bash
dpkg-deb --contents percorso/al/file.deb
```

- Estrae i contenuti del pacchetto in una cartella:

```bash
dpkg-deb --extract percorso/al/file.deb percorso/alla/cartella
```

- Crea una pacchetto a partire da una cartella specificata:

```bash
dpkg-deb --build percorso/alla/cartella
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Agno94](mailto:agnophi@gmail.com) | apt*, dpkg*: add Italian translation (#4854) | 2020-11-02T13:08:24 | [a722b14d8608](https://github.com/tldr-pages/tldr/commit/a722b14d86085d614175c300539e3ccd8b957a48)

