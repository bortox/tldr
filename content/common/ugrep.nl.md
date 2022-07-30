---
author: ['Dr. Robert van Engelen']
date: 1656269315
title: "ugrep"
description: "ugrep, Ultrasnelle bestandszoeker met interactive UI."
categories: "common"
---
> Meer informatie: <https://github.com/Genivia/ugrep>.

- Open een interactieve TUI om recursief bestanden te zoeken (CTRL-Z voor hulp):

```bash
ugrep --query
```

- Zoek recursief met een regex zoekpatroon in de huidige directory naar passende bestanden:

```bash
ugrep "zoekpatroon"
```

- Zoek een gegeven bestand of bestanden in een gegeven directory en laat de passende regelnummers zien:

```bash
ugrep --line-number "zoekpatroon" pad/naar/bestand_of_directory
```

- Zoek recursief in de huidige directory en geef een lijst met passende bestanden:

```bash
ugrep --files-with-matches "zoekpatroon"
```

- Zoek "fuzzy" met maximaal 3 extra, missende of verwisselende karakters in het patroon:

```bash
ugrep --fuzzy=3 "zoekpatroon"
```

- Zoek passende gecomprimeerde bestanden, zip en tar archieven recursief in de huidige directory:

```bash
ugrep --decompress "zoekpatroon"
```

- Zoek alleen naar bestanden met namen die overeenkomen met een passende `foo*.???` glob patroon:

```bash
ugrep --glob="foo*.???" "zoekpatroon"
```

- Zoek alleen passende bestanden van het type C++ (gebruik `--type=list` voor een lijst van typenamen):

```bash
ugrep --type=cpp "zoekpatroon"
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Dr. Robert van Engelen](mailto:genivia-inc@users.noreply.github.com) | ugrep: add page (#7972) | 2022-06-26T20:48:35 | [803e0814a61d](https://github.com/tldr-pages/tldr/commit/803e0814a61d3661a582e7afda749c8c4f4e333a)

