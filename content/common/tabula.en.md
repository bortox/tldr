---
author: ['Marco Bonelli', 'pxgamer', 'Hayden Schiff']
date: 1559564381
title: "tabula, TLDR Pages"
description: "tabula, Extract tables from PDF files."
categories: "common"
---
> More information: <https://tabula.technology>.

- Extract all tables from a PDF to a CSV file:

```bash
tabula -o file.csv file.pdf
```

- Extract all tables from a PDF to a JSON file:

```bash
tabula --format JSON -o file.json file.pdf
```

- Extract tables from pages 1, 2, 3, and 6 of a PDF:

```bash
tabula --pages 1-3,6 file.pdf
```

- Extract tables from page 1 of a PDF, guessing which portion of the page to examine:

```bash
tabula --guess --pages 1 file.pdf
```

- Extract all tables from a PDF, using ruling lines to determine cell boundaries:

```bash
tabula --spreadsheet file.pdf
```

- Extract all tables from a PDF, using blank space to determine cell boundaries:

```bash
tabula --no-spreadsheet file.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | tabula: add link to homepage | 2019-05-14T19:58:59 | [40fd17629ca8](https://github.com/tldr-pages/tldr/commit/40fd17629ca8d5905a494299df7b28ee68755681)
[Hayden Schiff](mailto:oxguy3@gmail.com) | tabula: added alt format example also made ordering of arguments consistent | 2016-01-22T05:01:44 | [5a9da6c4d684](https://github.com/tldr-pages/tldr/commit/5a9da6c4d684af6648b1865d73dc92063cf31a5f)
[Hayden Schiff](mailto:oxguy3@gmail.com) | tabula: add page | 2016-01-22T04:58:30 | [dfd83b5565e8](https://github.com/tldr-pages/tldr/commit/dfd83b5565e8ba28f87fe6a6389356c974bf699f)

