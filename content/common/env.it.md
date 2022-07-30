---
author: ['Dario Vladović', 'Marco Bonelli', 'marchersimon']
date: 1617292466
title: "env"
description: "env, Mostra le variabili d'ambiente o esegui un programma in un ambiente modificato."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/env>.

- Mostra le variabili d'ambiente:

```bash
env
```

- Esegui un programma. Utilizzato spesso in script dopo lo shebang (#!) per cercare il percorso del programma:

```bash
env programma
```

- Resetta l'ambiente ed esegui un programma:

```bash
env -i programma
```

- Rimuovi una variabile dall'ambiente ed esegui un programma:

```bash
env -u variabile programma
```

- Setta una variabile ed esegui un programma:

```bash
env variabile=valore programma
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | env: add more information link (#5607) | 2021-03-30T15:57:12 | [fed21f3974b4](https://github.com/tldr-pages/tldr/commit/fed21f3974b4d2efe402133ff8d94a04bcf981ce)
[Marco Bonelli](mailto:marco@mebeim.net) | env: add Italian translation. | 2019-10-05T15:25:51 | [86465a69ec27](https://github.com/tldr-pages/tldr/commit/86465a69ec275a37c2c7d1ed513a7369578d46ea)

