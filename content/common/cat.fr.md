---
author: ['Patrice Denis', 'David Bariod', 'Dario Vladović', 'Nicolas Kosinski', 'bl-ue', 'marchersimon', 'julien']
date: 1633592259
title: "cat, TLDR Pages"
description: "cat, Affiche et concatène le contenu d'un ou plusieurs fichiers."
categories: "common"
---
> Plus d'informations : <https://www.gnu.org/software/coreutils/cat>.

- Affiche le contenu d'un fichier sur la sortie standard :

```bash
cat fichier
```

- Concatène le contenu de plusieurs fichiers vers le fichier de destination :

```bash
cat fichier1 fichier2 > fichier_de_destination
```

- Ajoute le contenu d'un ficher à la fin du fichier de destination :

```bash
cat fichier1 fichier2 >> fichier_de_destination
```

- Numérote toutes les lignes affichées :

```bash
cat -n fichier
```

- Affiche les caractères non-imprimables ainsi que les caractères d'espacement (en utilisant le préfixe `M-` si non-ASCII) :

```bash
cat -v -t -e fichier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cat: change more information link (#5551) | 2021-03-30T12:31:55 | [3d97ba7785c1](https://github.com/tldr-pages/tldr/commit/3d97ba7785c175e55c9c9ac06f1f20b08837ea5d)
[Patrice Denis](mailto:patrice.denis@gmail.com) | cat: add more info link and update French translation (#5497) | 2021-03-24T22:57:14 | [ea469862762d](https://github.com/tldr-pages/tldr/commit/ea469862762d2762a6a81a0cf85210b057195c6c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[julien](mailto:git@julienc.io) | cat: fix French punctuation and missing translations | 2019-10-26T17:59:51 | [dad999edbe87](https://github.com/tldr-pages/tldr/commit/dad999edbe8794af51a57f2adbd631a11ec1b69f)
[David Bariod](mailto:davidriod@googlemail.com) | cat: add French translation (#3142) | 2019-06-27T22:17:42 | [9ca3c785c5eb](https://github.com/tldr-pages/tldr/commit/9ca3c785c5eba7e7b03d9e64f7e8925c15657623)

