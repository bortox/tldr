---
author: ['Carlo Federico Vescovo', 'Kyle']
date: 1629747204
title: "airport"
description: "airport, Strumento di configurazione delle reti senza fili."
categories: "osx"
---
> Maggiori informazioni: <https://ss64.com/osx/airport.html>.

- Mostra le informazioni relative allo stato attuale delle connessioni senza fili:

```bash
airport -I
```

- Intercetta il traffico delle connessioni senza fili sul primo canale:

```bash
airport sniff 1
```

- Ricerca le reti senza fili disponibili:

```bash
airport -s
```

- Disassocia dalla rete airport corrente:

```bash
sudo airport -z
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Carlo Federico Vescovo](mailto:vescovocarlofederico@gmail.com) | afinfo, afplay, airport: add Italian translation (#4449) | 2020-10-05T16:34:56 | [9a956cff058d](https://github.com/tldr-pages/tldr/commit/9a956cff058d275e09be284a4ead2f43faf9a37d)

