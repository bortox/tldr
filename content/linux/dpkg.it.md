---
author: ['Axel Navarro', 'Franz', 'Agno94']
date: 1641649180
title: "dpkg"
description: "dpkg, Gestore di pacchetti Debian."
categories: "linux"
---
> Alcuni comandi aggiuntivi, come `dpkg deb`, hanno la propria documentazione.

> Maggiori informazioni: <https://manpages.debian.org/latest/dpkg/dpkg.html>.

- Installa un pacchetto:

```bash
dpkg -i percorso/al/file.deb
```

- Rimuove un pacchetto:

```bash
dpkg -r nome_del_pacchetto
```

- Elenca i pacchetti installati:

```bash
dpkg -l espressione_per_la_ricerca
```

- Elenca i contenuti di un pacchetto:

```bash
dpkg -L nome_del_pacchetto
```

- Elenca i contenuti di un file pacchetto locale:

```bash
dpkg -c percorso/al/file.deb
```

- Trova a quale pacchetto appartiene un file:

```bash
dpkg -S filename
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Franz](mailto:franz.f1032@gmail.com) | *: mention subcommands in Italian translation (#6804) | 2021-10-05T15:01:09 | [e13e67b1711e](https://github.com/tldr-pages/tldr/commit/e13e67b1711e4112cca0cc4d07521c0cf901290c)
[Agno94](mailto:agnophi@gmail.com) | apt*, dpkg*: add Italian translation (#4854) | 2020-11-02T13:08:24 | [a722b14d8608](https://github.com/tldr-pages/tldr/commit/a722b14d86085d614175c300539e3ccd8b957a48)

