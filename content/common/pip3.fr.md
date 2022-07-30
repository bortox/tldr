---
author: ['bl-ue', 'Ivor Benderavage', 'Seth Falco', 'marchersimon']
date: 1633592259
title: "pip3"
description: "pip3, Gestionnaire des paquets pour Python."
categories: "common"
---
> Plus d'informations : <https://pip.pypa.io>.

- Recherche un paquet :

```bash
pip3 search paquet
```

- Installe un paquet :

```bash
pip3 install paquet
```

- Installe une version particulière d'un paquet :

```bash
pip3 install paquet==version
```

- Met à jour un paquet :

```bash
pip3 install --upgrade paquet
```

- Désinstalle un paquet :

```bash
pip3 uninstall paquet
```

- Sauvegarde une liste des paquets installés :

```bash
pip3 freeze > requirements.txt
```

- Installe des paquets à partir d'un fichier :

```bash
pip3 install --requirement requirements.txt
```

- Affiche les informations d'un paquet installé :

```bash
pip3 show paquet
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Seth Falco](mailto:seth@falco.fun) | pip3: fix argument spelling (#6140) | 2021-06-18T03:52:17 | [f50ae7e90575](https://github.com/tldr-pages/tldr/commit/f50ae7e90575c96caf4175bf38497df2edce06d3)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | pipenv: add example for not dev packages (#4880) | 2020-11-01T14:11:33 | [e009d7ceba4a](https://github.com/tldr-pages/tldr/commit/e009d7ceba4a21a7920c47f78f4f2d2bf6810854)

