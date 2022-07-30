---
author: ['Nicolas Hansse']
date: 1658321754
title: "acyclic"
description: "acyclic, Construit un graphe orienté acyclique en inversant quelques sommets."
categories: "common"
---
> Filtres Graphviz : `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> Plus d'informations : <https://graphviz.org/pdf/acyclic.1.pdf>.

- Construit un graphe orienté acyclique en inversant quelques sommets :

```bash
acyclic chemin/vers/entrée.gv > chemin/vers/sortie.gv
```

- Affiche si un graphe est acyclique, possède une boucle ou est non-dirigé, ne produit pas de graphe en sortie :

```bash
acyclic -v -n chemin/vers/entrée.gv
```

- Affiche l'aide d' `acyclic` :

```bash
acyclic -?
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | acyclic: add French translation (#8194) | 2022-07-20T14:55:54 | [2a01bb7b7cdd](https://github.com/tldr-pages/tldr/commit/2a01bb7b7cdd4414cc8a8213b2ce29e75d46419f)

