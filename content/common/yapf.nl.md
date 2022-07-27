---
author: ['Florian B']
date: 1615670983
title: "yapf, TLDR Pages"
description: "yapf, Python stijlgidschecker."
categories: "common"
---
> Meer informatie: <https://github.com/google/yapf>.

- Print de geformateerde diff die zal optreden uit:

```bash
yapf --diff pad/naar/bestand
```

- Print de geformateerde diff uit en breng de wijzigingen aan in het bestand:

```bash
yapf --diff --in-place pad/naar/bestand
```

- Formatteer alle Python-bestanden recursief in een map in parallel:

```bash
yapf --recursive --in-place --style pep8 --parallel pad/naar/map
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Florian B](mailto:florianb053@gmail.com) | yapf: add page and Dutch translation (#5435) | 2021-03-13T22:29:43 | [79ebb31e06cc](https://github.com/tldr-pages/tldr/commit/79ebb31e06cca2df10b6dd8d70ea6f6acc811c4b)

