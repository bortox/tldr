---
author: ['Dario Vladović', 'David Bariod', 'Nicolas Kosinski', 'julien', 'bl-ue', 'Patrice Denis', 'marchersimon']
date: 1633592259
title: "chmod"
description: "chmod, Modifie les droits d'accès d'un fichier ou d'un répertoire."
categories: "common"
---
> Plus d'informations : <https://www.gnu.org/software/coreutils/chmod>.

- Donne les droits d'e[x]écution à l'[u]tilisateur auquel le fichier appartient :

```bash
chmod u+x fichier
```

- Donne à l'utilisateur les droits de lecture (r) et d'écriture (w) sur un fichier/répertoire :

```bash
chmod u+rw fichier_ou_repertoire
```

- Enlève les droits d'exécution pour le [g]roupe :

```bash
chmod g-x fichier
```

- Donne à tous (a) les utilisateurs les droits de lecture et d'exécution :

```bash
chmod a+rx fichier
```

- Donne aux autres utilisateurs (qui sont dans un autre groupe) les mêmes droits que ceux du groupe propriétaire :

```bash
chmod o=g fichier
```

- Retire tous les droits aux autres (o) utilisateurs :

```bash
chmod o= fichier
```

- Modifie les permissions récursivement en donnant aux membres du groupe et aux autres utilisateurs le droit d'écriture :

```bash
chmod -R g+w,o+w repertoire
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chmod: change more information link (#5547) | 2021-03-29T22:28:18 | [db38dff0e9db](https://github.com/tldr-pages/tldr/commit/db38dff0e9db1d880e7406df340d16509470fbbb)
[Patrice Denis](mailto:patrice.denis@gmail.com) | chmod: add more info link and update French translation (#5496) | 2021-03-24T23:00:22 | [f45463dbd074](https://github.com/tldr-pages/tldr/commit/f45463dbd07431a1fee2763ae4d1f1900d517864)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[julien](mailto:git@julienc.io) | chmod: fix French punctuation | 2019-10-26T17:59:51 | [52500c104fe5](https://github.com/tldr-pages/tldr/commit/52500c104fe530110cbeb14879699983a63ffe09)
[David Bariod](mailto:davidriod@googlemail.com) | chmod: add French translation (#3182) | 2019-07-10T14:17:37 | [8e41ac1328d1](https://github.com/tldr-pages/tldr/commit/8e41ac1328d1e24f640b75635c0969b89c164e29)

