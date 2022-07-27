---
author: ['Charlie', 'marchersimon']
date: 1633112881
title: "bash, TLDR Pages"
description: "bash, Bourne-Again SHell."
categories: "common"
---
> `sh`-ondersteunende commandoregel-interpreteerder.

> Meer informatie: <https://gnu.org/software/bash/>.

- Start interactieve shell:

```bash
bash
```

- Voer een commando uit:

```bash
bash -c "commando"
```

- Voer commando's van bestand uit:

```bash
bash bestand.sh
```

- Voer commando's van bestand uit, en print alle uitgevoerde commando's naar de terminal:

```bash
bash -x bestand.sh
```

- Voer commando's van bestand uit, en stop bij de eerste fout:

```bash
bash -e bestand.sh
```

- Voer commando's van stdin uit:

```bash
bash -s
```

- Print de versieinformatie van bash (gebruik `echo $BASH_VERSION` om alleen de versie te krijgen zonder licentie):

```bash
bash --version
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Charlie](mailto:10348289+Cxarli@users.noreply.github.com) | 7z, adb, bash, cargo, cd: add Dutch translation (#4913) | 2020-11-01T15:35:52 | [b854a40530cb](https://github.com/tldr-pages/tldr/commit/b854a40530cbc5895537147ea2fb16d038003e83)

