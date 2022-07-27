---
author: ['Jeroen Knoops']
date: 1634311346
title: "alias, TLDR Pages"
description: "alias, Maakt een alias aan -- Woorden die vervangen woorden door commando's."
categories: "common"
---
> Een alias blijft bestaan in de huidige shell sessie, tenzij gedefinieerd in de configuratie van de shell, bijvoorbeeld in `~/.bashrc`.

> Meer informatie: <https://tldp.org/LDP/abs/html/aliases.html>.

- Overzicht alle aliases:

```bash
alias
```

- Maak een generieke alias aan:

```bash
alias woord="commando"
```

- Laat het gekoppelde commando zien van een gegeven alias:

```bash
alias woord
```

- Verwijdert een alias:

```bash
unalias woord
```

- Maak van `rm` een interactief commando:

```bash
alias rm="rm -i"
```

- Maak een alias `la` aan als korte schrijfwijze van `ls -a`:

```bash
alias la="ls -a"
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Jeroen Knoops](mailto:jeroen.knoops@philips.com) | alias: add Dutch translation | 2021-10-15T17:22:26 | [d69a4a2ef766](https://github.com/tldr-pages/tldr/commit/d69a4a2ef766af8a280da646010f8b9412380ea5)

