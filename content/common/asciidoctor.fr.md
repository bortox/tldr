---
author: ['Nicolas Hansse']
date: 1659761507
title: "asciidoctor"
description: "asciidoctor, Un processeur qui convertit des fichiers AsciiDoc vers un format publiable."
categories: "common"
---
> Plus d'informations : <https://docs.asciidoctor.org>.

- Convertis un fichier `.adoc` vers un fichier HTML (le format de sortie par défaut) :

```bash
asciidoctor chemin/vers/fichier.adoc
```

- Convertis un fichier `.adoc` vers un fichier HTML et lie une feuille de style CSS :

```bash
asciidoctor -a stylesheet=chemin/vers/feuille_de_style.css chemin/vers/fichier.adoc
```

- Convertis un fichier `.adoc` vers un fichier HTML embarqué, en enlevant tout sauf le body :

```bash
asciidoctor --embedded chemin/vers/fichier.adoc
```

- Convertis un fichier `.adoc` vers un PDF en utilisant la librairie `asciidoctor-pdf` :

```bash
asciidoctor --backend=pdf --require=asciidoctor-pdf chemin/vers/fichier.adoc
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | asciidoctor, asciinema: add French translation (#8279) | 2022-08-06T06:51:47 | [3182701c8c7e](https://github.com/tldr-pages/tldr/commit/3182701c8c7e4154fecad94a4ecc6d376ca2d9fb)

