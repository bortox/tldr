---
author: ['Florian B']
date: 1617388293
title: "autopep8"
description: "autopep8, Formatteer Python-code conform de PEP 8-stijlgids."
categories: "common"
---
> Meer informatie: <https://github.com/hhatto/autopep8>.

- Formateer een bestand naar stdout, met een ingestelde maximale toegestane regellengte:

```bash
autopep8 pad/naar/bestand.py --max-line-length lengte
```

- Formateer een bestand, geef een diff weer met de wijzigingen:

```bash
autopep8 --diff pad/naar/bestand.py
```

- Formatteer het bestand en sla de wijzigingen op:

```bash
autopep8 --in-place pad/naar/bestand.py
```

- Formatteer de bestanden recursief in een map en sla deze wijzigingen op:

```bash
autopep8 --in-place --recursive pad/naar/map
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Florian B](mailto:gn0mish@protonmail.com) | autopep8: add page (#5645) | 2021-04-02T20:31:33 | [4a7fab0b97c7](https://github.com/tldr-pages/tldr/commit/4a7fab0b97c715ac6d09c63f260a0678f3b6d551)

