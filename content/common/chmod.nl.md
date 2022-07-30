---
author: ['Dario Vladović', 'marchersimon', 'bl-ue', 'Charlie']
date: 1617292466
title: "chmod"
description: "chmod, Verander de toegangstoestemmingen van een bestand of map."
categories: "common"
---
> Meer informatie: <https://www.gnu.org/software/coreutils/chmod>.

- Geef een gebruiker ([u]ser) die het bestand beheert het recht om deze uit te voeren (e[x]ecute):

```bash
chmod u+x bestand
```

- Geef de gebruiker ([u]ser) het recht om een bestand of map te lezen ([r]ead) en schrijven ([w]rite):

```bash
chmod u+rw bestand_of_map
```

- Haal uitvoertoestemming (e[x]ecute) voor een bestand weg van de [g]roep:

```bash
chmod g-x bestand
```

- Geef [a]lle gebruikers toegang om een bestand te lezen ([r]ead) en schrijven ([w]rite):

```bash
chmod a+rx bestand
```

- Geef anderen ([o]thers) die niet in de groep van de beheerder zitten, dezelfde rechten als de [g]roep:

```bash
chmod o=g bestand
```

- Haal alle rechten van de anderen ([o]thers) weg:

```bash
chmod o= bestand
```

- Verander de toestemmingen recursief, waarbij de [g]roep en anderen ([o]thers) de mogelijkheid tot schrijven ([w]rite) krijgen:

```bash
chmod -R g+w,o+w map
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chmod: change more information link (#5547) | 2021-03-29T22:28:18 | [db38dff0e9db](https://github.com/tldr-pages/tldr/commit/db38dff0e9db1d880e7406df340d16509470fbbb)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Charlie](mailto:10348289+Cxarli@users.noreply.github.com) | chgrp, chmod, chown, chroot: add Dutch translations (#4914) | 2020-11-01T15:27:37 | [189a07dbace5](https://github.com/tldr-pages/tldr/commit/189a07dbace58fe0f4c036ecd2aeb0fcc4773c08)

