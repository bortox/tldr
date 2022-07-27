---
author: ['Gatien']
date: 1650411679
title: "powershell, TLDR Pages"
description: "powershell, Interface en ligne de commande et langage de script spécialement conçu pour l'administration système."
categories: "windows"
---
> Plus d'informations : <https://docs.microsoft.com/windows-server/administration/windows-commands/powershell>.

- Démarre une session Windows PowerShell dans une fenêtre d'invite de commande :

```bash
powershell
```

- Charge un fichier de console PowerShell spécifique :

```bash
powershell -PSConsoleFile chemin/vers/fichier
```

- Démarre une session avec une version spécifiée de PowerShell :

```bash
powershell -Version version
```

- Empêche l’interface système de se fermer après avoir exécuté les commandes de démarrage :

```bash
powershell -NoExit
```

- Décrive le format des données envoyées à PowerShell :

```bash
powershell -InputFormat Texte|XML
```

- Détermine comment la sortie de PowerShell est formatée :

```bash
powershell -OutputFormat Texte|XML
```

- Affiche l'aide :

```bash
powershell -Help
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Gatien](mailto:Gatien.vilain@outlook.fr) | chromium, code, gimp, powershell : add French translation (#8037) * translate code in French * translate powershell in French * switch [...] | 2022-04-20T01:41:19 | [fad355136f6b](https://github.com/tldr-pages/tldr/commit/fad355136f6b12812e588e2d05b9dec91dd88f8b)

