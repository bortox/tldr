---
author: ['Paradact']
date: 1635465071
title: "vim, TLDR Pages"
description: "vim, Vim (Vi IMproved), een command-line tekst bewerker, geeft toegang tot verschillende manieren van tekst manipulatie."
categories: "common"
---
> Drukken op `i` begint invoegmodus. `<Esc>` begint normale modus, wat toegang geeft tot de Vim commando's.

> Meer informatie: <https://www.vim.org>.

- Open een bestand:

```bash
vim pad/naar/bestand
```

- Open een bestand bij een bepaald regelnummer:

```bash
vim +regel_nummer pad/naar/bestand
```

- bekijk de handleiding van Vim:

```bash
:help<Enter>
```

- Opslaan en Afsluiten:

```bash
:wq<Enter>
```

- Maak de laatste verandering ongedaan:

```bash
u
```

- Zoek een patroon in het bestand (druk op `n`/`N` om naar de volgende/vorige overeenkomst te gaan):

```bash
/zoek_patroon<Enter>
```

- Voer een reguliere expressie substitutie uit in het hele bestand:

```bash
:%s/reguliere_expressie/vervanging/g<Enter>
```

- Geef de regelnummers weer:

```bash
:set nu<Enter>
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Paradact](mailto:44441385+Paradact@users.noreply.github.com) | vi, vim: add Dutch translation (#7255) | 2021-10-29T01:51:11 | [56b2781988cc](https://github.com/tldr-pages/tldr/commit/56b2781988ccae30e4fcfc75efc010a744b79805)

