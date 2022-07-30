---
author: ['Marco Bonelli', 'marchersimon']
date: 1618756407
title: "badblocks"
description: "badblocks, Cerca blocchi corrotti in un dispositivo."
categories: "common"
---
> Alcuni utilizzi di badblocks possono avere esiti non reversibili, come perdita dei dati o anche della tabella delle partizioni di un disco.

> Maggiori informazioni: <https://manned.org/badblocks>.

- Cerca blocchi corrotti in un disco utilizzando un test non distruttivo in sola lettura:

```bash
sudo badblocks /dev/sda
```

- Cerca blocchi corrotti in un disco non montato con un test non distruttivo in lettura e scrittura:

```bash
sudo badblocks -n /dev/sda
```

- Cerca blocchi corrotti in un disco non montato con un test distruttivo in scrittura:

```bash
sudo badblocks -w /dev/sda
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | badblocks: fix link | 2021-04-18T16:33:27 | [9dcaa79cdbd6](https://github.com/tldr-pages/tldr/commit/9dcaa79cdbd60c09b0c06e17d2c7e689a3ab4126)
[marchersimon](mailto:marchersimon@zohomail.eu) | badblocks: add link | 2021-04-18T16:33:27 | [962f1bc5ed08](https://github.com/tldr-pages/tldr/commit/962f1bc5ed08dfe6e4cdb2541bc0fa805e91af71)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | badblocks: add Italian translation. | 2019-01-28T19:10:19 | [94d304b77296](https://github.com/tldr-pages/tldr/commit/94d304b77296ff7ab84ae91229bba58031b6120e)

