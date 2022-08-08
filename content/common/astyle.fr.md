---
author: ['Nicolas Hansse']
date: 1659887262
title: "astyle"
description: "astyle, Indente, formate, et embelli du code source pour des languages de programmation comme C, C++, C# et Java."
categories: "common"
---
> Pendant l'exécution, une copie du fichier original est créé avec un ".orig" suffixé au nom de fichier original.

> Plus d'informations : <http://astyle.sourceforge.net/>.

- Applique le style par défaut de 4 espaces pour l'indentation et pas de changement de formatage :

```bash
astyle fichier_source
```

- Applique le style Java avec le style `attached` :

```bash
astyle --style=java chemin/vers/fichier
```

- Applique le style `allman` :

```bash
astyle --style=allman chemin/vers/fichier
```

- Applique une indentation personnalisé avec des espaces. Choisi entre 2 et 20 espaces :

```bash
astyle --indent=spaces=nombre_d_espaces chemin/vers/fichier
```

- Applique une indentation personnalisé avec des tabulations. Choisi entre 2 et 20 tabulations :

```bash
astyle --indent=tab=nombre_de_tabulations chemin/vers/fichier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | astyle, atoum: add French translation (#8305) | 2022-08-07T17:47:42 | [404e05cf822d](https://github.com/tldr-pages/tldr/commit/404e05cf822db5a9d7b8e96505dccc9e796c4851)

