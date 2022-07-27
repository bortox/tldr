---
author: ['CARE-COLIN Thibaut', 'David Bariod', 'Nicolas Kosinski', 'bl-ue', 'marchersimon', 'julien']
date: 1633592259
title: "awk, TLDR Pages"
description: "awk, Langage de programmation polyvalent pour travailler sur des fichiers."
categories: "common"
---
> Plus d'informations : <https://github.com/onetrueawk/awk>.

- Affiche la cinquième colonne (ou le champ) dans un fichier qui utilise des espaces comme séparateur :

```bash
awk '{print $5}' nom_de_fichier
```

- Affiche la deuxième colonne dans des lignes contenant "quelque-chose" dans un fichier qui utilise des espaces comme séparateur :

```bash
awk '/quelque-chose/ {print $2}' nom_de_fichier
```

- Affiche la dernière colonne de chaque ligne d'un fichier en utilisant une virgule (au lieu des espaces) comme séparateur :

```bash
awk -F ',' '{print $NF}' nom_de_fichier
```

- Additionne les valeurs de la première colonne des lignes d'un fichier et affiche le total :

```bash
awk '{s+=$1} END {print s}' nom_de_fichier
```

- Additionne les valeurs de la première colonne des lignes d'un fichier et affiche ces valeurs puis affiche le total :

```bash
awk '{s+=$1; print $1} END {print "--------"; print s}' nom_de_fichier
```

- Affiche une ligne sur trois en partant de la première ligne :

```bash
awk 'NR%3==1' nom_de_fichier
```

- Affiche les lignes dont la valeur de la colonne 10 vaut la valeur recherchée :

```bash
awk '($10 == valeur)'
```

- Affiche les lignes dont la valeur de la colonne 10 est comprise entre un min et un max :

```bash
awk '($10 >= valeur_min && $10 <= valeur_max)'
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | awk: add operators match (#4606) | 2020-11-01T15:42:00 | [d78a7103fe7a](https://github.com/tldr-pages/tldr/commit/d78a7103fe7a55ee8ec04cd1ed8eea12f3dbb3a0)
[julien](mailto:git@julienc.io) | awk: reworded header for French translation | 2019-10-26T17:59:51 | [b23b02c86f17](https://github.com/tldr-pages/tldr/commit/b23b02c86f170636a2b0cf78f9b3a38e7710594b)
[julien](mailto:git@julienc.io) | awk: fix French punctuation | 2019-10-26T17:59:51 | [9ae6b1866a5d](https://github.com/tldr-pages/tldr/commit/9ae6b1866a5d5e4f58cf3fc07b601ac53e9f9af6)
[David Bariod](mailto:davidriod@googlemail.com) | awk: add french translation (#3186) | 2019-07-16T02:24:02 | [7a99ad4f7201](https://github.com/tldr-pages/tldr/commit/7a99ad4f72013157f4760ddb90819988732dd582)

