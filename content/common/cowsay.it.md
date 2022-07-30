---
author: ['Nicolas Kosinski', 'Marco Bonelli']
date: 1618337238
title: "cowsay"
description: "cowsay, Genera un personaggio ASCII (di default una mucca) che dice o pensa qualcosa."
categories: "common"
---
> Maggiori informazioni: <https://github.com/tnalpgge/rank-amateur-cowsay>.

- Stampa una mucca ASCII che dice "Hello world":

```bash
cowsay "Hello world"
```

- Usa il testo da standard input per il fumetto:

```bash
echo "Ciao" | cowsay
```

- Elenca tutti i personaggi disponibili:

```bash
cowsay -l
```

- Stampa un drago ASCII che dice "Ciao":

```bash
cowsay -f dragon "Ciao"
```

- Stampa una mucca ASCII sballata che pensa:

```bash
cowthink -s "Sono solo una mucca, non un grande pensatore..."
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | cowsay: fix commands for zsh (#5742) | 2021-04-13T20:07:18 | [6c4068b01901](https://github.com/tldr-pages/tldr/commit/6c4068b01901f36d53686965b5c851d797309482)
[Marco Bonelli](mailto:marco@mebeim.net) | cowsay: add stdin example | 2019-06-16T05:28:55 | [6398e538eddd](https://github.com/tldr-pages/tldr/commit/6398e538eddd4cd0d6daab1771b5401779be67a3)
[Marco Bonelli](mailto:marco@mebeim.net) | cowsay: simplify example. | 2019-06-16T05:28:55 | [5bd8d80998ee](https://github.com/tldr-pages/tldr/commit/5bd8d80998ee56fcc2b03c034146e77fb601a0b2)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cowsay: add Italian translation. | 2019-06-10T01:35:02 | [34650102ec0b](https://github.com/tldr-pages/tldr/commit/34650102ec0b56167b66b3cf2fced404eb2cfa02)

