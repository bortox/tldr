---
author: ['Marco Bonelli', 'Schneider', 'Simone Ragusa', 'bl-ue']
date: 1619003118
title: "ab, TLDR Pages"
description: "ab, Strumento di benchmarking di Apache. Il più semplice modo per eseguire un test sul carico del server."
categories: "common"
---
> Maggiori informazioni: <https://httpd.apache.org/docs/current/programs/ab.html>.

- Esegui 100 richieste HTTP GET ad un dato URL:

```bash
ab -n 100 url
```

- Esegui 100 richieste HTTP GET ad un dato URL, processandone fino a 10 contemporaneamente:

```bash
ab -n 100 -c 10 url
```

- Esegui 100 richieste HTTP POST a un dato URL, utilizzando un payload JSON tramite file:

```bash
ab -n 100 -T application/json -p percorso/a/file.json url
```

- Usa HTTP [K]eep Alive, ovvero esegui richieste multiple in una stessa sessione HTTP:

```bash
ab -k url
```

- Setta il massimo numero di secondi per il benchmarking:

```bash
ab -t secondi url
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Simone Ragusa](mailto:simone99.as@gmail.com) | 7z, ab, ack: update Italian translation | 2021-04-21T13:05:18 | [d028ac125e63](https://github.com/tldr-pages/tldr/commit/d028ac125e63ed0021d4633038dfa88b407e9100)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | ab: update grammar; update link (#5433) | 2021-03-13T22:44:59 | [8f2ed246f761](https://github.com/tldr-pages/tldr/commit/8f2ed246f7614df6e815b9eefae053a0f64df920)
[Marco Bonelli](mailto:marco@mebeim.net) | ab: fix typo. | 2019-06-10T01:35:02 | [ae602cf0645d](https://github.com/tldr-pages/tldr/commit/ae602cf0645dfe14972469b2ce86477fd7ada545)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\ab.md: add homepage | 2019-05-14T19:40:23 | [2472385a368f](https://github.com/tldr-pages/tldr/commit/2472385a368f0e2389641964716423344f462b70)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: add italian translations (#2692) Translated 13 pages into italian: 7z 7za 7zr ab abduco ack adb ag airpaste alias [...] | 2019-01-11T01:34:17 | [1286509fe557](https://github.com/tldr-pages/tldr/commit/1286509fe557aaa701a1ebe07ce0c5c0b7ef6959)

