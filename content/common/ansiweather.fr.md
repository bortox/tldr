---
author: ['Nicolas Hansse']
date: 1658330478
title: "ansiweather"
description: "ansiweather, Un script Shell pour afficher les conditions météo actuelles dans votre terminal."
categories: "common"
---
> Plus d'informations : <https://github.com/fcambus/ansiweather>.

- Affiche une prévision avec le système métrique pour les 5 prochains jours dans la ville de Paris, France :

```bash
ansiweather -u metric -f 5 -l Paris,FR
```

- Affiche une prévision avec des symboles et les données d'ensoleillement pour votre position actuelle :

```bash
ansiweather -s true -d true
```

- Affiche une prévision avec les données sur le vent et l'humidité pour votre position actuelle :

```bash
ansiweather -w true -h true
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ansiweather, ant: add French translation (#8223) * ansiweather, ant: add French translation * chore: code review | 2022-07-20T17:21:18 | [a7e8269783f6](https://github.com/tldr-pages/tldr/commit/a7e8269783f6034ad59e413de1f6a2187fa896c5)

