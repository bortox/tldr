---
author: ['bl-ue', 'Charlie', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "chown"
description: "chown, Verander gebruiker- en groepsbeheer van bestanden en mappen."
categories: "common"
---
> Meer informatie: <https://www.gnu.org/software/coreutils/chown>.

- Verander gebruikkersbeheerder van een bestand/map:

```bash
chown gebruiker pad/naar/bestand_of_map
```

- Verander de gebruikersbeheerder en -groep van een bestand of map:

```bash
chown gebruiker:groep pad/naar/bestand_of_map
```

- Verander recursief de beheerder van een map en alle inhoud:

```bash
chown -R gebruiker pad/naar/bestand_of_map
```

- Verander de gebruiker van een symbolische link:

```bash
chown -h gebruiker pad/naar/symlink
```

- Verander de beheerder van een bestand of map naar dezelfde als een referentiebestand:

```bash
chown --reference=pad/naar/referentiebestand pad/naar/bestand_of_map
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chown: add more information link (#5555) | 2021-03-30T15:29:42 | [8d147522d127](https://github.com/tldr-pages/tldr/commit/8d147522d127f65aca087b791bf2deb46a43f59d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Charlie](mailto:10348289+Cxarli@users.noreply.github.com) | chgrp, chmod, chown, chroot: add Dutch translations (#4914) | 2020-11-01T15:27:37 | [189a07dbace5](https://github.com/tldr-pages/tldr/commit/189a07dbace58fe0f4c036ecd2aeb0fcc4773c08)

