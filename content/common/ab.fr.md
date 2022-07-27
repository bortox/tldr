---
author: ['Nicolas Hansse']
date: 1644837146
title: "ab, TLDR Pages"
description: "ab, Outil d'analyse pour serveur Apache HTTP."
categories: "common"
---
> Plus d'informations : <https://httpd.apache.org/docs/current/programs/ab.html>.

- Exécute 100 requêtes HTTP GET sur une URL donnée :

```bash
ab -n 100 url
```

- Exécute 100 requêtes HTTP GET en parallèle par groupe de 10, sur une URL :

```bash
ab -n 100 -c 10 url
```

- Exécute 100 requêtes HTTP POST sur une URL, en utilisant un contenu JSON depuis un fichier :

```bash
ab -n 100 -T application/json -p chemin/vers/le/fichier.json url
```

- Utilise la fonctionalitée HTTP Keep Alive pour exécuter plusieurs requêtes dans la même session HTTP :

```bash
ab -k url
```

- Fixe le nombre maximum de secondes d'exécution pour l'analyse :

```bash
ab -t 60 url
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | aapt, ab: add French translation (#7723) * aapt, ab: add French translation * Update pages.fr/common/aapt.md Co-authored-by: Emily [...] | 2022-02-14T12:12:26 | [b1326296cda4](https://github.com/tldr-pages/tldr/commit/b1326296cda429c77ea5754896b0ad68f8883ca8)

