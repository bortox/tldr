---
author: ['Ivor Benderavage', 'lincc', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1633592259
title: "ifconfig, TLDR Pages"
description: "ifconfig, Configurateur des interfaces réseau."
categories: "common"
---
> Plus d'informations : <https://net-tools.sourceforge.io/man/ifconfig.8.html>.

- Affiche les paramètres de réseau d'un adaptateur ethernet :

```bash
ifconfig eth0
```

- Affiche les détails de toutes les interfaces, y compris les interfaces désactivées :

```bash
ifconfig -a
```

- Désactive l'interface eth0 :

```bash
ifconfig eth0 down
```

- Active l'interface eth0 :

```bash
ifconfig eth0 up
```

- Assigne une adresse IP à l'interface eth0 :

```bash
ifconfig eth0 addresse_ip
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | ifconfig: add more information link (#6218) Co-authored-by: Muhammad Falak R Wani <falakreyaz@gmail.com> Co-authored-by: CleanMachine1 [...] | 2021-07-12T08:51:22 | [03e2e3389e47](https://github.com/tldr-pages/tldr/commit/03e2e3389e47edab092e1336c704fc5f5f2b7ba6)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | Update pages.fr/common/ifconfig.md Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2020-10-24T15:03:06 | [9d1d1c2be467](https://github.com/tldr-pages/tldr/commit/9d1d1c2be467cbc708c33ed6c5b35829c636f170)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | Update pages.fr/common/ifconfig.md Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2020-10-24T15:03:06 | [0d4eb384952d](https://github.com/tldr-pages/tldr/commit/0d4eb384952d97a9bb2fc037d9b6d557ab27afbb)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | Update pages.fr/common/ifconfig.md Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2020-10-24T15:03:06 | [f18a029d90e3](https://github.com/tldr-pages/tldr/commit/f18a029d90e31a3f960bf1b602796b0888bf1bc2)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | Update pages.fr/common/ifconfig.md Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2020-10-24T15:03:06 | [fd661abfe401](https://github.com/tldr-pages/tldr/commit/fd661abfe401cea102a2cd67c9e6d101b035c7df)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | ifconfig: add spaces before colons | 2020-10-24T15:03:06 | [8899a482ca35](https://github.com/tldr-pages/tldr/commit/8899a482ca358ba59dbc21e1a98f79f2817df453)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | ifconfig, lua, mkdir: add French translation | 2020-10-24T15:03:06 | [7d6ea639f118](https://github.com/tldr-pages/tldr/commit/7d6ea639f118a0eb38143791d14db114006344b7)

