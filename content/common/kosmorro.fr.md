---
author: ['Nicolas Kosinski', 'Jérôme Deuchnord', 'bl-ue', 'marchersimon']
date: 1633592259
title: "kosmorro, TLDR Pages"
description: "kosmorro, Calcule les éphémérides et les évènements pour une date donnée, à un emplacement donné sur Terre."
categories: "common"
---
> Plus d'informations : <http://kosmorro.space>.

- Obtenir les éphémérides pour Paris (France) :

```bash
kosmorro --latitude=48.7996 --longitude=2.3511
```

- Obtenir les éphémérides pour Paris (France), sur le fuseau horaire UTC+2 :

```bash
kosmorro --latitude=48.7996 --longitude=2.3511 --timezone=2
```

- Obtenir les éphémérides du 9 juin 2020 pour Paris (France) :

```bash
kosmorro --latitude=48.7996 --longitude=2.3511 --date=2020-06-09
```

- Générer un fichier PDF (TeXLive doit être installé) :

```bash
kosmorro --format=pdf --output=chemin/vers/le/fichier.pdf
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Jérôme Deuchnord](mailto:Deuchnord@users.noreply.github.com) | kosmorro: add page (#4498) | 2020-10-08T05:44:43 | [d51d17a5570f](https://github.com/tldr-pages/tldr/commit/d51d17a5570feee4cb785467384a0c5f9ddea5cd)

