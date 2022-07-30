---
author: ['Jeroen Knoops']
date: 1634311346
title: "asciinema"
description: "asciinema, Neemt en speelt terminal sessies af, en deelt hem optioneel op asciinema.org."
categories: "common"
---
> Meer informatie: <https://asciinema.org/>.

- Associeer de lokale installatie van `asciinema` met het asciinema.org account:

```bash
asciinema auth
```

- Maak een nieuwe opname (gebruiker krijgt een vraag om het lokaal op te slaan of te uploaden als de opname klaar is):

```bash
asciinema rec
```

- Maak een nieuwe opname en sla het op in een lokaal bestand:

```bash
asciinema rec pad/naar/bestand.cast
```

- Speelt een terminal opname of vanaf een lokaal bestand:

```bash
asciinema play pad/naar/bestand.cast
```

- Speelt een terminal opname of vanaf asciinema.org:

```bash
asciinema play https://asciinema.org/a/cast_id
```

- Maakt een nieuwe opname met een inactieve tijd van maximaal 2,5 seconden:

```bash
asciinema rec -i 2.5
```

- Laat de volledige inhoud zien van een lokaal opgeslagen opname:

```bash
asciinema cat pad/naar/bestand.cast
```

- Slaat een lokaal opgeslagen terminal sessie op bij asciinema.org:

```bash
asciinema upload pad/naar/bestand.cast
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Jeroen Knoops](mailto:jeroen.knoops@philips.com) | asciinema: add Dutch translation | 2021-10-15T17:22:26 | [f5ad666ba88f](https://github.com/tldr-pages/tldr/commit/f5ad666ba88fc2fbda43b9fef4568fd199ee76e7)

