---
author: ['Nicolas Hansse', 'Ivor Benderavage', 'Noah', 'bl-ue', 'marchersimon']
date: 1636291516
title: "pip"
description: "pip, Gestionnaire des paquets pour Python."
categories: "common"
---
> Certaines commandes comme `pip install` ont leur propre documentation.

> Plus d'informations : <https://pip.pypa.io>.

- Installe un paquet :

```bash
pip install paquet
```

- Installe une version particulière d'un paquet :

```bash
pip install paquet==version
```

- Installe un paquet dans le répertoire utilisateur au lieu de l'emplacement par défaut système :

```bash
pip install --user paquet
```

- Met à jour un paquet :

```bash
pip install --upgrade paquet
```

- Désinstalle un paquet :

```bash
pip uninstall paquet
```

- Sauvegarde une liste des paquets installés :

```bash
pip freeze > requirements.txt
```

- Installe des paquets à partir d'un fichier :

```bash
pip install --requirement requirements.txt
```

- Affiche les informations d'un paquet installé :

```bash
pip show paquet
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Noah](mailto:nbaltunian@gmail.com) | pip: synchronize long options, formatting and add --user example (#6605) | 2021-11-07T14:25:16 | [4042138a51c8](https://github.com/tldr-pages/tldr/commit/4042138a51c845a4fff7744f4c6ffc76cdc14e12)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | *: mention subcommands in FR translations (#6823) | 2021-10-06T22:45:59 | [b0e0a6e58cfb](https://github.com/tldr-pages/tldr/commit/b0e0a6e58cfbff6cb7041a4d37b1b46ddac79941)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | pipenv: add example for not dev packages (#4880) | 2020-11-01T14:11:33 | [e009d7ceba4a](https://github.com/tldr-pages/tldr/commit/e009d7ceba4a21a7920c47f78f4f2d2bf6810854)

