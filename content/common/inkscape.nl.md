---
author: ['Jennifer']
date: 1602539192
title: "inkscape"
description: "inkscape, Een SVG (Scalable Vector Graphics) bewerkingsprogramma."
categories: "common"
---
> Voor Inkscape versies tot en met 0.92.x, gebruik -e in plaats van -o.

> Meer informatie: <https://inkscape.org>.

- Open een SVG-bestand in de Inkscape GUI:

```bash
inkscape bestandsnaam.svg
```

- Exporteer een SVG-bestand in een bitmap met het standaardformaat (PNG) en de standaardresolutie (96 DPI):

```bash
inkscape bestandsnaam.svg -o bestandsnaam.png
```

- Exporteer een SVG-bestand in een bitmap van 600x400 pixels (vervorming van de aspectverhouding mogelijk):

```bash
inkscape bestandsnaam.svg -o bestandsnaam.png -w 600 -h 400
```

- Exporteer de tekening (selectiekader van alle objecten) van een SVG-bestand in een bitmap:

```bash
inkscape bestandsnaam.svg -o bestandsnaam.png -D
```

- Exporteer een enkel object, gezien zijn ID, in een bitmap:

```bash
inkscape bestandsnaam.svg -i id -o object.png
```

- Exporteer een SVG-document naar PDF, converteer alle teksten naar paden:

```bash
inkscape bestandsnaam.svg -o bestandsnaam.pdf --export-text-to-path
```

- Dupliceer het object met id="pad123", roteer het duplicaat 90 graden, sla het bestand op, en sluit Inkscape af:

```bash
inkscape bestandsnaam.svg --select=path123 --verb="EditDuplicate;ObjectRotate90;FileSave;FileQuit"
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Jennifer](mailto:42771751+JenniX3@users.noreply.github.com) | inkscape: add Dutch translation (#4609) * inkscape: add Dutch translation * fix build errors * Update pages.nl/common/inkscape.md Co- [...] | 2020-10-12T23:46:32 | [85a1c064b6d4](https://github.com/tldr-pages/tldr/commit/85a1c064b6d472e6182bd3be4267201f187a83fb)

