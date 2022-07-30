---
author: ['Schneider', 'Marco Bonelli']
date: 1559564381
title: "avrdude"
description: "avrdude, Driver per il programmatore di microcontrollori Atmel AVR."
categories: "common"
---
> Maggiori informazioni: <https://www.nongnu.org/avrdude/>.

- Leggi dal microcontrollore AVR:

```bash
avrdude -p dispositivo_AVR -c id_programmatore -U flash:r:file.hex:i
```

- Scrivi sul microcontrollore AVR:

```bash
avrdude -p dispositivo_AVR -c id_programmatore -U flash:w:file.hex
```

- Elenca dispositivi AVR disponibili:

```bash
avrdude -p \?
```

- Elenca programmatori AVR disponibili:

```bash
avrdude -c \?
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\avrdude.md: add homepage | 2019-05-14T19:40:23 | [266884f30935](https://github.com/tldr-pages/tldr/commit/266884f309358af501a69a222af1dd3c37e36c9b)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | avrdude: add Italian translation. | 2019-01-28T19:10:19 | [0d29259356d8](https://github.com/tldr-pages/tldr/commit/0d29259356d8c3061facc074185496138ba60aaa)

