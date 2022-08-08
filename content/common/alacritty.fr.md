---
author: ['Nicolas Hansse']
date: 1659863512
title: "alacritty"
description: "alacritty, Emulateur de terminal propulsé par GPU, Multi-plateforme."
categories: "common"
---
> Plus d'informations : <https://github.com/alacritty/alacritty>.

- Ouvre une nouvelle fenêtre Alacritty :

```bash
alacritty
```

- Lance dans un dossier spécifique :

```bash
alacritty --working-directory chemin/vers/dossier
```

- Lance une commande dans une nouvelle fenêtre Alacritty :

```bash
alacritty -e commande
```

- Utilise un autre fichier de configuration (le fichier par défault étant `$XDG_CONFIG_HOME/alacritty/alacritty.yml`) :

```bash
alacritty --config-file chemin/vers/config.yml
```

- Lance avec la mise à jour en live dès que la configuration est modifiée ( peu également être activé par défaut dans `alacritty.yml`) :

```bash
alacritty --live-config-reload --config-file chemin/vers/config.yml
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ajson, alacritty, alex: add French translation (#8208) | 2022-08-07T11:11:52 | [328292383b5c](https://github.com/tldr-pages/tldr/commit/328292383b5c408f9a2b28b9b01faa80583699a8)

