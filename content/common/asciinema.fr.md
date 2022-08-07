---
author: ['Nicolas Hansse']
date: 1659761507
title: "asciinema"
description: "asciinema, Enregistre et rejoue les sessions de terminal, et également partageable sur asciinema.org."
categories: "common"
---
> Plus d'informations : <https://asciinema.org/>.

- Associe l’installation locale de `asciinema` avec un compte asciinema.org :

```bash
asciinema auth
```

- Crée un nouvel enregistrement (une fois fini, l'utilisateur sera questionné pour l'enregistrer localement ou l'envoyer en ligne) :

```bash
asciinema rec
```

- Crée un nouvel enregistrement et l'enregistre dans un fichier local :

```bash
asciinema rec chemin/vers/fichier.cast
```

- Rejoue un enregistrement depuis un fichier local :

```bash
asciinema play chemin/vers/fichier.cast
```

- Rejoue un enregistrement depuis asciinema.org :

```bash
asciinema play https://asciinema.org/a/id_d_enregistrement
```

- Crée un nouvel enregistrement, en limitant le temps d’inactivité au maximum à 2.5 secondes :

```bash
asciinema rec -i 2.5
```

- Affiche la sortie complète d'un enregistrement local :

```bash
asciinema cat chemin/vers/fichier.cast
```

- Envoie un enregistrement local vers asciinema.org :

```bash
asciinema upload chemin/vers/fichier.cast
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | asciidoctor, asciinema: add French translation (#8279) | 2022-08-06T06:51:47 | [3182701c8c7e](https://github.com/tldr-pages/tldr/commit/3182701c8c7e4154fecad94a4ecc6d376ca2d9fb)

