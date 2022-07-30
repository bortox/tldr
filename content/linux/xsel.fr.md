---
author: ['marchersimon', 'Alexandre ZANNI']
date: 1659075216
title: "xsel, TLDR Pages"
description: "xsel, Outil de sélection et de manipulation du presse-papiers X11."
categories: "linux"
---
> Plus d'informations : <https://manned.org/xsel>.

- Utilise la sortie d'une commande comme entrée du presse-papiers (équivalent de `Ctrl + C`) :

```bash
echo 123 | xsel -ib
```

- Utilise le contenu d'un fichier comme entrée du presse-papiers :

```bash
cat fichier | xsel -ib
```

- Affiche le contenu du presse-papiers dans le terminal (équivalent à `Ctrl + V`) :

```bash
xsel -ob
```

- Sortie du contenu du presse-papiers dans un fichier :

```bash
xsel -ob > fichier
```

- Efface le presse-papiers :

```bash
xsel -cb
```

- Affiche le contenu de la sélection primaire X11 dans le terminal (équivalent à un clic du milieu de la souris) :

```bash
xsel -op
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Alexandre ZANNI](mailto:16578570+noraj@users.noreply.github.com) | xsel: add French translation (#6672) | 2021-10-05T21:21:30 | [ab21c0dfed86](https://github.com/tldr-pages/tldr/commit/ab21c0dfed869784175fb9ddb8fc0c282124974c)

