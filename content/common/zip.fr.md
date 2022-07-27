---
author: ['Patrice Denis', 'sebastientinel', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1633592259
title: "zip, TLDR Pages"
description: "zip, Empaquette et compresse (archive) les fichiers en un fichier zip."
categories: "common"
---
> Plus d'informations : <https://manned.org/zip>.

- Empaquette et compresse [r]écursivement un répertoire et son contenu :

```bash
zip -r archive.zip chemin/du/répertoire
```

- E[x]clure des fichiers de l'archive :

```bash
zip -r archive.zip chemin/vers/le/répertoire -x chemin/des/fichiers/exclus
```

- Archive un répertoire et son contenu avec le plus haut niveau [9] de compression :

```bash
zip -r -9 archive.zip chemin/du/répertoire
```

- Empaquette et compresse plusieurs répertoires et fichiers :

```bash
zip -r archive.zip chemin/du/répertoire1 chemin/du/répertoire2 chemin/du/fichier
```

- Crée une archive chiffrée (l'utilisateur sera sollicité pour saisir le mot de passe) :

```bash
zip -e -r archive.zip chemin/du/répertoire
```

- Ajoute des fichiers à une archive existante :

```bash
zip archive.zip chemin/du/fichier
```

- Supprime des fichiers d'une archive existante :

```bash
zip -d archive.zip "foo/*.tmp"
```

- Archive un répertoire et son contenu en plusieurs fichiers zip [s]cindés (ex : des fichiers de 3 Go) :

```bash
zip -r -s 3g archive.zip chemin/du/répertoire
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | z, zip, zless, zola, zopflipng, zoxide: add French translation (#4727) | 2020-10-19T19:04:15 | [ba78b756508c](https://github.com/tldr-pages/tldr/commit/ba78b756508c46ec6a44bd178b7f084fc2e50503)

