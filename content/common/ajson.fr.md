---
author: ['Nicolas Hansse']
date: 1659863512
title: "ajson"
description: "ajson, Exécute un JSONPath sur un objet JSON."
categories: "common"
---
> Plus d'informations : <https://github.com/spyzhov/ajson>.

- Lis un JSON depuis un fichier et exécute une expression JSONPath spécifique :

```bash
ajson '$..json[?(@.path)]' chemin/vers/fichier.json
```

- Lis un JSON depuis l'entrée standard et exécute une expression JSONPath spécifique :

```bash
cat chemin/vers/fichier.json | ajson '$..json[?(@.path)]'
```

- Lis un JSON depuis une URL et évalue une expression JSONPath spécifique :

```bash
ajson 'avg($..price)' 'https://exemple.com/api/'
```

- Lis un JSON simple et calcule une valeur :

```bash
echo '3' | ajson '2 * pi * $'
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ajson, alacritty, alex: add French translation (#8208) | 2022-08-07T11:11:52 | [328292383b5c](https://github.com/tldr-pages/tldr/commit/328292383b5c408f9a2b28b9b01faa80583699a8)

