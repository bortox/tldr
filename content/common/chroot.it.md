---
author: ['Marco Bonelli', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "chroot, TLDR Pages"
description: "chroot, Esegui un comando o una shell interattiva con una speciale root directory."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/chroot>.

- Esegui un comando con una diversa root directory:

```bash
chroot /percorso/alla/nuova/root comando
```

- Specifica utente e gruppo (ID o nome) da usare:

```bash
chroot --userspec=utente:gruppo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chroot: add more information link (#5602) | 2021-03-30T15:50:36 | [b8f38025f36c](https://github.com/tldr-pages/tldr/commit/b8f38025f36c58be3d109949f4badf9e062b43e0)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | chroot: add Italian translation. | 2019-03-03T23:44:18 | [aa16a7a7ec6e](https://github.com/tldr-pages/tldr/commit/aa16a7a7ec6ecebbef4768c4b722c3df23e18599)

