---
author: ['Charlie', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "chroot, TLDR Pages"
description: "chroot, Voer commando of interactieve shell uit met een speciale hoofdmap."
categories: "common"
---
> Meer informatie: <https://www.gnu.org/software/coreutils/chroot>.

- Voer commando uit met gegeven hoofdmap:

```bash
chroot pad/naar/nieuwe/hoofdmap commando
```

- Specificeer gebruiker en groep (ID of naam) om te gebruiken:

```bash
chroot --userspec=gebruiker:groep
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chroot: add more information link (#5602) | 2021-03-30T15:50:36 | [b8f38025f36c](https://github.com/tldr-pages/tldr/commit/b8f38025f36c58be3d109949f4badf9e062b43e0)
[Charlie](mailto:10348289+Cxarli@users.noreply.github.com) | chgrp, chmod, chown, chroot: add Dutch translations (#4914) | 2020-11-01T15:27:37 | [189a07dbace5](https://github.com/tldr-pages/tldr/commit/189a07dbace58fe0f4c036ecd2aeb0fcc4773c08)

