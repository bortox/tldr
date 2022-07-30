---
author: ["Robby O'Connor", 'Guido Lena Cota', 'Marco Bonelli', 'bl-ue', 'marchersimon']
date: 1633592259
title: "tar"
description: "tar, Utilitaire d'archivage."
categories: "common"
---
> Souvent combiné avec une méthode de compression, telle que gzip ou bzip2.

> Plus d'informations : <https://www.gnu.org/software/tar>.

- Créer une archive à partir de fichiers :

```bash
tar cf cible.tar fichier1 fichier2 fichier3
```

- Créer une archive gzip :

```bash
tar czf cible.tar.gz fichier1 fichier2 fichier3
```

- Extraie une archive (compressée) dans le dossier courant :

```bash
tar xf source.tar[.gz|.bz2|.xz]
```

- Extraie une archive dans un dossier cible :

```bash
tar xf source.tar -C dossier
```

- Créer une archive compressée, en utilisant le suffixe de l'archive pour déterminer le programme de compression :

```bash
tar caf cible.tar.xz fichier1 fichier2 fichier3
```

- Lister le contenu d'une archive tar :

```bash
tar tvf source.tar
```

- Extraire les fichiers correspondant au motif :

```bash
tar xf source.tar --wildcards "*.html"
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Robby O'Connor](mailto:rob@oconnor.ninja) | tar: fix bzip to bzip2 in command description (#5264) | 2021-02-13T04:53:30 | [5cd65c2850e0](https://github.com/tldr-pages/tldr/commit/5cd65c2850e0f3186af032337f596dbb7c5be79a)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | tar: add French translation (#3732) * tar: add French translation Co-authored-by: Hugo D. (jabesq) <jabesq@gmail.com> * Typo Co- [...] | 2020-01-04T15:50:55 | [2fc20251a9ca](https://github.com/tldr-pages/tldr/commit/2fc20251a9ca6f16374795c469f2cf39e2c8cf16)

