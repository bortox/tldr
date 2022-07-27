---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1633112881
title: "dep, TLDR Pages"
description: "dep, Strumento di gestione delle dipendenze per progetti Go."
categories: "common"
---
> Maggiori informazioni: <https://deployer.org>.

- Inizializza la directory corrente come radice di un progetto Go:

```bash
dep init
```

- Installa dipendenze mancanti (scannerizza `Gopkg.toml` ed i file `.go`):

```bash
dep ensure
```

- Mostra lo stato delle dipendenze di un progetto:

```bash
dep status
```

- Aggiungi una dipendenza al progetto:

```bash
dep ensure -add url_pacchetto
```

- Aggiorna le versioni bloccate (in `Gopkg.lock`) di tutte le dipendenze:

```bash
dep ensure -update
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | dep: add Italian translation. | 2019-06-10T01:35:02 | [f3634a78c396](https://github.com/tldr-pages/tldr/commit/f3634a78c396c8e4ed17bf2acaf8e29e94e9f6f9)

