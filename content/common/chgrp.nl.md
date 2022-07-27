---
author: ['Charlie', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "chgrp, TLDR Pages"
description: "chgrp, Verander beheerdersgroep van bestanden en mappen."
categories: "common"
---
> Meer informatie: <https://www.gnu.org/software/coreutils/chgrp>.

- Verander beheerdergroep van een bestand of map:

```bash
chgrp groep pad/naar/bestand_of_map
```

- Verander recursief de beheerdersgroep van een map en alle bestanden erin:

```bash
chgrp -R groep pad/naar/map
```

- Verander beheerdersgroep van een symbolische link:

```bash
chgrp -h groep pad/naar/symlink
```

- Verander de beheerdersgroep van een bestand/map naar de permissies van een referentiebestand:

```bash
chgrp --reference=pad/naar/referentiebestand pad/naar/bestand_of_map
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chgrp: add more information link (#5554) | 2021-03-30T12:33:21 | [1bee28dd6572](https://github.com/tldr-pages/tldr/commit/1bee28dd6572c855d7cdb2ffd88e05794a8cfc86)
[Charlie](mailto:10348289+Cxarli@users.noreply.github.com) | chgrp, chmod, chown, chroot: add Dutch translations (#4914) | 2020-11-01T15:27:37 | [189a07dbace5](https://github.com/tldr-pages/tldr/commit/189a07dbace58fe0f4c036ecd2aeb0fcc4773c08)

