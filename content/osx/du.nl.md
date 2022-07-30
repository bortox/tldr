---
author: ['Jeroen Knoops', 'marchersimon']
date: 1634848494
title: "du"
description: "du, Disk gebruik: schat en groepeer bestand en directory ruimte gebruik."
categories: "osx"
---
> Meer informatie: <https://ss64.com/osx/du.html>.

- Toont de grootte van een directory en mogelijke sub-directories, met een gegeven eenheid (KiB/MiB/GiB):

```bash
du -k|m|g pad/naar/directory
```

- Toont de grootte van een directory en mogelijke sub-directories, met een leesbaar unit formaat (bijvoorbeeld door het automatisch kiezen van een eenheid gebaseerd op grootte)):

```bash
du -h pad/naar/directory
```

- Toont de grootte van een enkele directory met een leesbaar eenheid formaat:

```bash
du -sh pad/naar/directory
```

- Toont de grootte in leesbare vorm van een directory met alle bestanden en directories:

```bash
du -ah pad/naar/directory
```

- Toont de grootte in leesbare vorm van een directory en alle sub-directories tot N niveaus diep:

```bash
du -h -d N pad/naar/directory
```

- Toont de grootte in leesbare vorm van alle `.jpg` bestanden in sub-directories van de huidige directory en laat een cumulatief totaal zien op het eind:

```bash
du -ch */*.jpg
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | du: fix wrong byte units (#7131) | 2021-10-21T22:34:54 | [0ddea62ffb82](https://github.com/tldr-pages/tldr/commit/0ddea62ffb822afabf0437c9a0d15258f13ce672)
[Jeroen Knoops](mailto:jeroen.knoops@philips.com) | du: add Dutch translation (#6843) | 2021-10-07T04:39:39 | [ea046b717d22](https://github.com/tldr-pages/tldr/commit/ea046b717d221200f77e5d74a97ff7c3031d5877)

