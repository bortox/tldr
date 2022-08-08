---
author: ['Nicolas Hansse']
date: 1659863512
title: "alex"
description: "alex, Un outil qui corrige les phrases insensible et inconsidérée (en Anglais uniquement)."
categories: "common"
---
> Il vous aide à trouver un genre, une polarité, une ethnie, un blasphème, ou autre inégalité en lisant un texte en anglais.

> Plus d'informations : <https://github.com/get-alex/alex>.

- Analyse un texte depuis l'entrée standard :

```bash
echo His network looks good | alex --stdin
```

- Analyse tous les fichiers dans le dossier courant :

```bash
alex
```

- Analyse un fichier spécifique :

```bash
alex fichiertexte.md
```

- Analyse tous les fichiers Markdown sauf `exemple.md`

```bash
alex *.md !exemple.md
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ajson, alacritty, alex: add French translation (#8208) | 2022-08-07T11:11:52 | [328292383b5c](https://github.com/tldr-pages/tldr/commit/328292383b5c408f9a2b28b9b01faa80583699a8)

