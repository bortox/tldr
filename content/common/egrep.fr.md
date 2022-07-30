---
author: ['Antoine Amara', 'lincc']
date: 1643487459
title: "egrep"
description: "egrep, Recherche de motifs dans un texte. Supporte la version étendues des expressions regulieres (`?`, `+`, `{}`, `()`, et `|`)."
categories: "common"
---
> Plus d'informations : <https://manned.org/egrep>.

- Recherche une chaîne de caractères précise :

```bash
egrep "chaîne_recherchée" chemin/vers/fichier
```

- Recherche une chaîne de caractères dans plusieurs fichiers :

```bash
egrep "chaîne_recherchée" chemin/vers/fichier1 chemin/vers/fichier2 chemin/vers/fichier3
```

- Utilise l'entrée standard au lieu d'un fichier :

```bash
cat chemin/vers/fichier | egrep chaîne_recherchée
```

- Affiche le nom du fichier avec la ligne correspondante pour chaque concordance :

```bash
egrep --with-filename --line-number "chaîne_recherchée" chemin/vers/fichier
```

- Recherche récursivement dans le dossier courant, en ignorant les fichiers binaires, une chaîne de caractères précise :

```bash
egrep --recursive --binary-files=without-match "chaîne_recherchée" chemin/vers/fichier
```

- Inverse le résultat pour exclure des chaînes de caractères spécifiques :

```bash
egrep --invert-match "chaîne_recherchée" chemin/vers/fichier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Antoine Amara](mailto:amara.antoine@gmail.com) | egrep: add French translation (#6958) | 2021-10-19T12:00:32 | [c4ae77ff68c7](https://github.com/tldr-pages/tldr/commit/c4ae77ff68c7e4a2e67d883eb9c76443a54fd6a9)

