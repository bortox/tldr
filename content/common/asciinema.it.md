---
author: ['Schneider', 'Marco Bonelli']
date: 1559564381
title: "asciinema"
description: "asciinema, Registra e riproduci sessioni di terminale, condividendole opzionalmente su asciiname.org."
categories: "common"
---
> Maggiori informazioni: <https://asciinema.org/>.

- Associa l'installazione locale di `asciiname` ad un account di asciiname.org:

```bash
asciinema auth
```

- Avvia una nuova registrazione (una volta terminata, verrà chiesto se caricarla o salvarla localmente):

```bash
asciinema rec
```

- Avvia una nuova registrazione e salvala come file locale:

```bash
asciinema rec nome_registrazione.cast
```

- Riproduci una sessione da un file locale:

```bash
asciinema play percorso/al/file.cast
```

- Riproducei una sessione da asciinema.org:

```bash
asciinema play https://asciinema.org/a/id_registrazione
```

- Avvia una nuova registrazione, limitando qualsiasi periodo di inattività a 2.5 secondi:

```bash
asciinema rec -i 2.5
```

- Stampa l'output completo di una sessione locale:

```bash
asciinema cat percorso/al/file.cast
```

- Carica una sessione locale su asciinama.org:

```bash
asciinema upload percorso/al/file.cast
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\asciinema.md: add homepage | 2019-05-14T19:40:23 | [0e1b2f6ad3f7](https://github.com/tldr-pages/tldr/commit/0e1b2f6ad3f79f67407f172c5ce5f3bfd5bba4e5)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | asciinema: add Italian translation. | 2019-01-28T19:10:19 | [7d65d67daa4c](https://github.com/tldr-pages/tldr/commit/7d65d67daa4c67a7e81b7b6d94e803f4947fbb42)

