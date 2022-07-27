---
author: ['Nicolas Hansse']
date: 1658041231
title: "amass db, TLDR Pages"
description: "amass db, Intéragie avec une base de données Amass."
categories: "common"
---
> Plus d'informations : <https://github.com/OWASP/Amass/blob/master/doc/user_guide.md#the-db-subcommand>.

- Liste toutes les énumérations performées pas la base de données :

```bash
amass db -dir chemin/vers/dossier_de_la_base_de_données -list
```

- Affiche les résultats pour un index d'énumération et un nom de domaine spécifiés :

```bash
amass db -dir chemin/vers/dossier_de_la_base_de_données -d nom_de_domaine -enum index_depuis_la liste -show
```

- Liste tous les sous-domaines trouvés pour un domaine inclus dans une énumération :

```bash
amass db -dir chemin/vers/dossier_de_la_base_de_données -d nom_de_domaine -enum index_depuis_la liste -names
```

- Affiche un sommaire des sous-domaines inclus dans une énumération :

```bash
amass db -dir chemin/vers/dossier_de_la_base_de_données -d nom_de_domaine -enum index_depuis_la liste -summary
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | amass, amass-db, amass-enum: add French translation (#8209) | 2022-07-17T09:00:31 | [97d47723bb66](https://github.com/tldr-pages/tldr/commit/97d47723bb660e92b33cc0a187eb572fa328bba5)

