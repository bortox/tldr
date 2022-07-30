---
author: ['Paradact']
date: 1635465013
title: "nano"
description: "nano, Simpele, makkelijk te gebruiken command-line tekst bewerker. Een verbeterde, gratis Pico kloon."
categories: "common"
---
> Meer informatie: <https://nano-editor.org>.

- Open een nieuw bestand in nano:

```bash
nano
```

- Open een specifiek bestand:

```bash
nano pad/naar/bestand
```

- Open een bepaald bestand, met de cursor gezet in een gegeven regel en kolom:

```bash
nano +regel,kolom pad/naar/bestand
```

- Open een bepaald bestand en zet 'soft wrapping' aan:

```bash
nano --softwrap pad/naar/bestand
```

- Open een bepaald bestand en spring nieuwe regels in volgens de inspringing van de vorige regel:

```bash
nano --autoindent pad/naar/bestand
```

- Open nano en maak een reservekopie (`bestand~`) bij het opslaan van veranderingen:

```bash
nano --backup pad/naar/bestand
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Paradact](mailto:44441385+Paradact@users.noreply.github.com) | nano: add Dutch translation (#7257) | 2021-10-29T01:50:13 | [1da96c46afb3](https://github.com/tldr-pages/tldr/commit/1da96c46afb38858aa0fd902b4e9904dbbe63370)

