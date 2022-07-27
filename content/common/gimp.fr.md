---
author: ['Gatien']
date: 1650411679
title: "gimp, TLDR Pages"
description: "gimp, Outil d'édition et de retouche d'image, libre et multiplateforme"
categories: "common"
---
> Voir aussi : `krita`.

> Plus d'informations : <https://docs.gimp.org/en/gimp-fire-up.html#gimp-concepts-running-command-line>.

- Démarre GIMP :

```bash
gimp
```

- Démarre sans l'écran de démarrage :

```bash
gimp --no-splash
```

- Ouvre les fichiers spécifiés :

```bash
gimp chemin/vers/image1 chemin/vers/image2 ...
```

- Démarre une nouvelle instance, même si une instance est déjà en cours d'exécution :

```bash
gimp --new-instance
```

- Affiche les erreurs et les avertissements sur la console au lieu de les afficher dans une boîte de dialogue :

```bash
gimp --console-messages
```

- Active les routines de débogage des signaux non fatals :

```bash
gimp --debug-handlers
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Gatien](mailto:Gatien.vilain@outlook.fr) | chromium, code, gimp, powershell : add French translation (#8037) * translate code in French * translate powershell in French * switch [...] | 2022-04-20T01:41:19 | [fad355136f6b](https://github.com/tldr-pages/tldr/commit/fad355136f6b12812e588e2d05b9dec91dd88f8b)

