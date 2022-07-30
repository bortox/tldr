---
author: ['Marco Bonelli', 'marchersimon']
date: 1618869951
title: "drill"
description: "drill, Esegui varie query DNS."
categories: "common"
---
> Maggiori informazioni: <https://manned.org/drill>.

- Mostra gli IP associati ad un hostname (record A):

```bash
drill esempio.com
```

- Lookup the mail server(s) associated with a given domain name (MX record):

```bash
drill mx esempio.com
```

- Recupera tutti i tipi di record per un dato dominio:

```bash
drill any esempio.com
```

- Specifica un server DNS alternativo da interrogare:

```bash
drill esempio.com @8.8.8.8
```

- Esegui un lookup DNS inverso su di un indirizzo IP (record PTR):

```bash
drill -x 8.8.8.8
```

- Esegui un tracciamento DNSSEC dai root server fino al dominio:

```bash
drill -TD esempio.com
```

- Mostra record DNSKEY per un dominio:

```bash
drill -s dnskey esempio.com
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Marco Bonelli](mailto:marco@mebeim.net) | drill: add Italian translation. | 2019-10-05T15:25:51 | [5c01cbd5f9ce](https://github.com/tldr-pages/tldr/commit/5c01cbd5f9ce5758f67be3ff339e5427318f8a70)

