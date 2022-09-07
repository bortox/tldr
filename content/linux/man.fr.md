---
author: ['Mia Combeau']
date: 1662480102
title: "man"
description: "man, Interface de consultation des pages du manuel de référence."
categories: "linux"
---
> Plus d'informations : <https://www.man7.org/linux/man-pages/man1/man.1.html>.

- Affiche la page de manuel d'une commande :

```bash
man commande
```

- Affiche la page de manuel de la section 7 d'une commande :

```bash
man 7 commande
```

- Liste toutes les sections dans lesquelles se trouve une commande :

```bash
man --whatis commande
```

- Affiche tous les chemins où se trouvent les pages de manuel :

```bash
man --path
```

- Affiche l'emplacement d'une page de manuel plutôt que la page elle-même :

```bash
man --where commande
```

- Affiche la page de manuel dans une langue particulière :

```bash
man --locale=fr_FR commande
```

- Cherche toutes les pages de manuel contenant la chaîne de caractères spécifée :

```bash
man --apropos "chaîne_de_caractères"
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Mia Combeau](mailto:52008667+mcombeau@users.noreply.github.com) | man: add French translation (#8464) | 2022-09-06T18:01:42 | [e5fda71c5b23](https://github.com/tldr-pages/tldr/commit/e5fda71c5b236729d7d47a92c47a847296878ef2)

