---
author: ['Franz', 'Marco Bonelli']
date: 1633438869
title: "conda"
description: "conda, Gestione pacchetti, dipendenze ed ambiente per qualsiasi linguaggio di programmazione."
categories: "common"
---
> Alcuni comandi aggiuntivi, come `conda create`, hanno la propria documentazione.

> Maggiori informazioni: <https://github.com/conda/conda>.

- Crea un nuovo ambiente, installandovi alcuni pacchetti:

```bash
conda create --name nome_ambiente python=2.7 matplotlib
```

- Elenca tutti gli ambienti:

```bash
conda info --envs
```

- Attiva o disattiva un ambiente:

```bash
conda activate|deactivate nome_ambiente
```

- Elimina un ambiente rimuovendo anche tutti i pacchetti:

```bash
conda remove --name nome_ambiente --all
```

- Cerca un determinato pacchetto nei canali di conda:

```bash
conda search package_name
```

- Installa pacchetti nell'ambiente corrente:

```bash
conda install python=3.4 numpy
```

- Elenca i pacchetti attualmente installati nell'ambiente corrente:

```bash
conda list
```

- Elimina pacchetti inutilizzati e cache:

```bash
conda clean --all
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Franz](mailto:franz.f1032@gmail.com) | *: mention subcommands in Italian translation (#6804) | 2021-10-05T15:01:09 | [e13e67b1711e](https://github.com/tldr-pages/tldr/commit/e13e67b1711e4112cca0cc4d07521c0cf901290c)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | conda: add Italian translation. | 2019-06-10T01:35:02 | [92c11d2e5a7e](https://github.com/tldr-pages/tldr/commit/92c11d2e5a7eefe320b6281e8a796ff21836a5ef)

