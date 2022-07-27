---
author: ['Gatien']
date: 1650411679
title: "chromium, TLDR Pages"
description: "chromium, Navigateur Web open source principalement développé et maintenu par Google."
categories: "common"
---
> Plus d'informations : <https://www.chromium.org/developers/how-tos/run-chromium-with-flags/>.

- Ouvre une URL ou un fichier spécifique :

```bash
chromium https://exemple.com|chemin/vers/fichier.html
```

- Ouvre en mode navigation privée :

```bash
chromium --incognito exemple.com
```

- Ouvre dans une nouvelle fenêtre :

```bash
chromium --new-window exemple.com
```

- Ouvre en mode application (sans barres d'outils, barre d'URL, boutons, etc) :

```bash
chromium --app=https://exemple.com
```

- Utilise un serveur proxy :

```bash
chromium --proxy-server="://hostname:66" exemple.com
```

- Ouvre dans un répertoire de profil personnalisé :

```bash
chromium --user-data-dir=chemin/vers/répertoire
```

- Ouvre sans validation CORS (utile pour tester une API) :

```bash
chromium --user-data-dir=chemin/vers/répertoire --disable-web-security
```

- Ouvre avec une fenêtre outils de développement pour chaque onglet ouvert :

```bash
chromium --auto-open-devtools-for-tabs
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Gatien](mailto:Gatien.vilain@outlook.fr) | chromium, code, gimp, powershell : add French translation (#8037) * translate code in French * translate powershell in French * switch [...] | 2022-04-20T01:41:19 | [fad355136f6b](https://github.com/tldr-pages/tldr/commit/fad355136f6b12812e588e2d05b9dec91dd88f8b)

