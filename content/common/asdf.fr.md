---
author: ['Nicolas Hansse']
date: 1643128657
title: "asdf"
description: "asdf, Interface en ligne de commande pour gérer les versions de différents paquets."
categories: "common"
---
> Plus d'informations : <https://asdf-vm.com>.

- Liste toutes les extensions disponibles :

```bash
asdf plugin-list-all
```

- Installe une extension :

```bash
asdf plugin-add nom
```

- Liste toutes les versions disponible d'un paquet :

```bash
asdf list-all nom
```

- Installe une version spécifique d'un paquet :

```bash
asdf install nom version
```

- Fixe au global une version d'un paquet :

```bash
asdf global nom version
```

- Fix en local la version d'un paquet :

```bash
asdf local nom version
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | asdf: add French translation (#7709) | 2022-01-25T17:37:37 | [46dacbc6ffba](https://github.com/tldr-pages/tldr/commit/46dacbc6ffbaead8eeda05b73da21608bd5a96eb)

