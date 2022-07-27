---
author: ['Nicolas Kosinski', 'Antoine Gaubert', 'marchersimon']
date: 1633592259
title: "fdupes, TLDR Pages"
description: "fdupes, Trouve les fichiers dupliqués dans les dossiers donnés."
categories: "common"
---
> Plus d'informations : <https://github.com/adrianlopezroche/fdupes>.

- Chercher dans un dossier :

```bash
fdupes dossier
```

- Chercher dans plusieurs dossiers :

```bash
fdupes dossier1 dossier2
```

- Chercher dans un dossier récursivement :

```bash
fdupes -r dossier
```

- Chercher dans plusieurs dossiers dont un récursivement :

```bash
fdupes dossier1 -R dossier2
```

- Chercher récursivement les dupliqués et demander les fichiers à conserver, supprimant les autres :

```bash
fdupes -rd dossier
```

- Chercher récursivement et supprimer les dupliqués automatiquement :

```bash
fdupes -rdN dossier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Antoine Gaubert](mailto:angauber@student.42lyon.fr) | fdupes: add delete and noprompt examples, add French translation (#5231) | 2021-02-04T19:14:01 | [0f064dff2c48](https://github.com/tldr-pages/tldr/commit/0f064dff2c48a12134a14faeb6b95200f04a64a5)

