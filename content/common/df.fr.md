---
author: ['William Belle', 'Dario Vladović', 'Nicolas Kosinski', 'bl-ue', 'marchersimon', 'julien']
date: 1633592259
title: "df, TLDR Pages"
description: "df, Montre un aperçu de l'utilisation de l'espace disque."
categories: "common"
---
> Plus d'informations : <https://www.gnu.org/software/coreutils/df>.

- Afficher tous les systèmes de fichiers et leur utilisation d'espace disque :

```bash
df
```

- Afficher tous les systèmes de fichiers et leur utilisation d'espace disque dans un format plus facilement :

```bash
df -h
```

- Afficher le système de fichiers et son utilisation d'espace disque rattaché au chemin donné :

```bash
df chemin/vers/fichier_ou_dossier
```

- Afficher des statistiques sur le nombre d'inodes disponibles :

```bash
df -i
```

- Afficher les systèmes de fichiers sauf ceux de types spécifiques :

```bash
df -x squashfs -x tmpfs
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | atom, clear, convert, df: sync French translations with English pages (#5797) | 2021-04-20T20:15:58 | [df7770ae6b58](https://github.com/tldr-pages/tldr/commit/df7770ae6b585a043f7a797de941a1c425acc6a5)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | df: add more information link (#5557) | 2021-03-30T12:23:41 | [0812ddae5287](https://github.com/tldr-pages/tldr/commit/0812ddae5287591cb1f8064bf5eb63033cadf39b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[William Belle](mailto:william.belle@gmail.com) | df: fix typo (#3903) | 2020-03-11T00:20:46 | [fec8b560a839](https://github.com/tldr-pages/tldr/commit/fec8b560a839f5d5d33c80fd2e46e14052d35b09)
[julien](mailto:git@julienc.io) | df: add French translation | 2019-10-27T17:33:39 | [f221760a5425](https://github.com/tldr-pages/tldr/commit/f221760a54259fe0d428688844c6bb2af7281af6)

