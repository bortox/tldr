---
author: ['marchersimon', 'Nicolas Hansse', 'Frieder Bluemle', 'lincc']
date: 1636372515
title: "mongo"
description: "mongo, Client shell pour MongoDB."
categories: "common"
---
> Plus d'informations : <https://docs.mongodb.com/manual/reference/program/mongo>.

- Connecte à une base de données (database) :

```bash
mongo nom_de_la_base_de_données
```

- Connecte à une base de données (database) sur un hôte (host) distant et un port donné :

```bash
mongo --host hôte --port port nom_de_la_base_de_données
```

- Connecte à une base de données (database) avec un nom d'utilisateur (username); L'utilisateur sera invité à saisir son mot de passe :

```bash
mongo --username nom_d'utilisateur nom_de_la_base_de_données --password
```

- Évalue une expression JavaScript sur une base de données (database) :

```bash
mongo --eval 'JSON.stringify(db.foo.findOne())' nom_de_la_base_de_données
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[Frieder Bluemle](mailto:frieder.bluemle@gmail.com) | mongo, node, nrm: fix typos | 2021-10-14T14:28:22 | [0e6984d78b78](https://github.com/tldr-pages/tldr/commit/0e6984d78b788605994dd7cae08a6afa4b86b312)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | mongo: add French translation (#6652) | 2021-10-04T16:08:01 | [90666387c71e](https://github.com/tldr-pages/tldr/commit/90666387c71ecaf14d7c6f5a0d2d0e35d36870e3)

