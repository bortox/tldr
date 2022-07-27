---
author: ['Marco Bonelli', 'marchersimon']
date: 1618756407
title: "arp, TLDR Pages"
description: "arp, Mostra e gestisci la cache ARP di sistema."
categories: "common"
---
> Maggiori informazioni: <https://manned.org/arp>.

- Mostra la tabella ARP corrente:

```bash
arp -a
```

- Elimina l'intera cache:

```bash
sudo arp -a -d
```

- Elimina una specifica voce:

```bash
arp -d indirizzo
```

- Crea una nuova voce:

```bash
arp -s indirizzo indirizzo_mac
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | arp: add link | 2021-04-18T16:33:27 | [f06702a5bcc3](https://github.com/tldr-pages/tldr/commit/f06702a5bcc36ee9323d8e467b27e65ed111ef23)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | arp: add Italian translation. | 2019-01-28T19:10:19 | [49d6fe9b077f](https://github.com/tldr-pages/tldr/commit/49d6fe9b077f00e64c63f781633425f11be9d451)

