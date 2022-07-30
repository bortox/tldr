---
author: ['Schneider', 'Marco Bonelli']
date: 1559564381
title: "bosh"
description: "bosh, Strumento da linea di comando per distribuire e gestire director BOSH."
categories: "common"
---
> Maggiori informazioni: <https://bosh.io/docs/cli-v2/>.

- Crea un alias locale per un director:

```bash
bosh alias-env nome_ambiente -e indirizzo_ip|url --ca-cert certificato_ca
```

- Elenca ambienti:

```bash
bosh environments
```

- Esegui il login al director:

```bash
bosh login -e ambiente 
```

- Elenca deployment (distribuzioni):

```bash
bosh -e ambiente deployments
```

- Elenca le macchine virtuali in un ambiente:

```bash
bosh -e ambiente vms -d deployment
```

- Avvia una sessione SSH in una macchina virtuale:

```bash
bosh -e ambiente ssh macchina_virtuale -d deployment
```

- Carica una stemcell:

```bash
bosh -e ambiente upload-stemcell file_stemcell|url
```

- Mostra la configurazione cloud attuale:

```bash
bosh -e ambiente cloud-config
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\bosh.md: add homepage | 2019-05-14T19:40:23 | [00b8efe0f24a](https://github.com/tldr-pages/tldr/commit/00b8efe0f24a26f55faaf9ceb2b916fb172829fb)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | bosh: add Italian translation. | 2019-01-28T19:10:19 | [08877bef9cb0](https://github.com/tldr-pages/tldr/commit/08877bef9cb00b8d18348df37bc098747fa912d7)

