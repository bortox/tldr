---
author: ['Dario Vladović', 'Reinhart Previano Koentjoro', 'David Bariod', 'Nicolas Kosinski', 'julien', 'bl-ue', 'marchersimon']
date: 1636534306
title: "install"
description: "install, Copie des fichiers et met à jour leurs attributs."
categories: "common"
---
> Copie des fichiers (souvent des exécutables) dans un répertoire système comme `/usr/local/bin` et leur donne les permissions et propriétaires appropriés.

> Plus d'informations : <https://www.gnu.org/software/coreutils/install>.

- Copie des fichiers vers une destination :

```bash
install chemin/fichier/source chemin/repertoire/destination
```

- Copie des fichiers vers une destination en mettant à jour leur propriétaire :

```bash
install --owner utilisateur chemin/fichier/source chemin/repertoire/destination
```

- Copie des fichiers vers une destination en mettant à jour leur groupe d'appartenance :

```bash
install --group utilisateur chemin/fichier/source chemin/repertoire/destination
```

- Copie des fichiers vers une destination en mettant à jour leur mode :

```bash
install --mode +x chemin/fichier/source chemin/repertoire/destination
```

- Copie des fichiers en mettant à jour leur dates d'accès et de modification à partir de leurs sources respectives :

```bash
install --preserve-timestamps chemin/fichier/source chemin/repertoire/destination
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | install: use long arguments format (#7403) | 2021-11-10T09:51:46 | [87e3e877fa3d](https://github.com/tldr-pages/tldr/commit/87e3e877fa3d6c0d7d2a7fe5100c908c76de8f57)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | install: add link (#5559) | 2021-03-30T09:30:44 | [718ea2fa10dc](https://github.com/tldr-pages/tldr/commit/718ea2fa10dc125e48e3fb10b3e8b8adbb86c0d0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[julien](mailto:git@julienc.io) | install: fix French punctuation and typos | 2019-10-26T17:59:51 | [b56ea287354a](https://github.com/tldr-pages/tldr/commit/b56ea287354acade198e9edaaaf296c130f04d79)
[David Bariod](mailto:davidriod@googlemail.com) | install: add French translation (#3158) | 2019-07-09T18:27:18 | [900a94e02d6d](https://github.com/tldr-pages/tldr/commit/900a94e02d6dbe4b6bf5a067d697793eea0d5eb6)

