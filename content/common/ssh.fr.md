---
author: ['David Bariod', 'lincc', 'Phil Enzler', 'julien', 'bl-ue', 'marchersimon']
date: 1636372515
title: "ssh"
description: "ssh, Secure Shell est un protocole utilisé pour se connecter de façon sécurisée à des systèmes distants."
categories: "common"
---
> On peut l'utiliser pour se connecter ou exécuter des commandes sur un serveur distant.

> Plus d'informations : <https://man.openbsd.org/ssh>.

- Se connecter à un serveur distant :

```bash
ssh utilisateur@hote_distant
```

- Se connecter à un serveur distant en utilisant une identité spécifique (clé privée) :

```bash
ssh -i chemin/vers/fichier_clef utilisateur@hote_distant
```

- Se connecter à un serveur distant en utilisant un port spécifique :

```bash
ssh utilisateur@hote_distant -p 2222
```

- Exécuter une commande sur un serveur distant :

```bash
ssh hote_distant commande -avec -options
```

- Tunnel SSH : Transfert par port dynamique (le SOCKS proxy se trouve sur localhost:1080) :

```bash
ssh -D 1080 utilisateur@hote_distant
```

- Tunnel SSH : Transfère un port spécifique (localhost:9999 vers example.org:80) en désactivant l'allocation de pseudo-[t]ty et l'exécution de commandes distantes :

```bash
ssh -L 9999:exemple.org:80 -N -T utilisateur@hote_distant
```

- Saut SSH : Se connecter sur un serveur distant à travers une machine de rebond (plusieurs machines de rebond peuvent être définies en les séparant par des virgules) :

```bash
ssh -J utilisateur@hote_de_rebond utilisateur@hote_distant
```

- Transfert d'agent : Transfère les informations d'authentification vers la machine distante (voir `man ssh_config` pour les options disponibles) :

```bash
ssh -A utilisateur@hote_distant
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Phil Enzler](mailto:phil@pushbutton.studio) | ssh: remove -C and use SOCKS port (#5771) | 2021-04-16T03:47:49 | [38c3b011dc62](https://github.com/tldr-pages/tldr/commit/38c3b011dc62cb45b7c2df5708bd3a6a02ec0fe3)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[julien](mailto:git@julienc.io) | ssh: fix French punctuation and standardize usage of infinitives | 2019-10-26T17:59:51 | [d347b9660ace](https://github.com/tldr-pages/tldr/commit/d347b9660ace39384f489295356786d00fd3c851)
[David Bariod](mailto:davidriod@googlemail.com) | ssh: add French translation (#3157) | 2019-07-09T17:58:42 | [a26f4b18eeb5](https://github.com/tldr-pages/tldr/commit/a26f4b18eeb5301c247a7d0cb75dc24d25b3c4f9)

