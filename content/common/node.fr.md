---
author: ['marchersimon', 'Nicolas Hansse', 'Frieder Bluemle']
date: 1634214502
title: "node"
description: "node, Plateforme JavaScript côté serveur."
categories: "common"
---
> Plus d'informations : <https://nodejs.org>.

- Éxecute un fichier JavaScript :

```bash
node chemin/vers/fichier
```

- Démarre un REPL (shell interactif) :

```bash
node
```

- Évalue du code JavaScript en le passant en argument :

```bash
node -e "code"
```

- Évalue et affiche le résultat, très utile pour voir les versions de dépendances node :

```bash
node -p "process.versions"
```

- Active l'inspecteur, mets en pause l'éxécution jusqu'à ce qu'un debugger soit connecté une fois que le code source est totalement interprété :

```bash
node --no-lazy --inspect-brk chemin/vers/fichier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Frieder Bluemle](mailto:frieder.bluemle@gmail.com) | mongo, node, nrm: fix typos | 2021-10-14T14:28:22 | [0e6984d78b78](https://github.com/tldr-pages/tldr/commit/0e6984d78b788605994dd7cae08a6afa4b86b312)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | node: add French translation (#6688) | 2021-10-04T18:05:40 | [bfb392f0c21e](https://github.com/tldr-pages/tldr/commit/bfb392f0c21e832421b02381447a774f45eede64)

