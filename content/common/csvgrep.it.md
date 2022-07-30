---
author: ['Marco Bonelli', 'Guido Lena Cota', 'marchersimon']
date: 1620637392
title: "csvgrep"
description: "csvgrep, Filtra righe CSV con stringhe e pattern matching."
categories: "common"
---
> Incluso in csvkit.

> Maggiori informazioni: <https://csvkit.readthedocs.io/en/latest/scripts/csvgrep.html>.

- Trova righe contenenti una certa stringa nella colonna 1:

```bash
csvgrep -c 1 -m stringa data.csv
```

- Trova righe per le quali le colonne 3 e 4 soddisfano una certa espressione regolare:

```bash
csvgrep -c 3,4 -r espressione_regolare data.csv
```

- Trova righe dove la colonna "nome" NON include la stringa "Mario Rossi":

```bash
csvgrep -i -c nome -m "Mario Rossi" data.csv
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | csvgrep: add Italian translation. | 2019-06-10T01:35:02 | [4867904b0159](https://github.com/tldr-pages/tldr/commit/4867904b01595ed0df57d99cfe28503164990419)

