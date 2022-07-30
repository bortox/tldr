---
author: ['Nicolas Hansse', 'Patrice Denis', 'Matthew Peveler', 'marchersimon']
date: 1633592259
title: "ip"
description: "ip, Affiche / manipule l'adressage, le routage, les interfaces et périphériques réseau, les règles de routage et les tunnels."
categories: "linux"
---
> Certaines commandes comme `ip address` ont leur propre documentation.

> Plus d'informations : <https://www.man7.org/linux/man-pages/man8/ip.8.html>.

- Liste les interfaces avec des infos détaillées :

```bash
ip address
```

- Liste les interfaces sur la couche réseau de façon synthétique :

```bash
ip -brief address
```

- Liste les interfaces sur la couche liaison de façon synthétique :

```bash
ip -brief link
```

- Affiche la table de routage :

```bash
ip route
```

- Affiche les voisins (table ARP) :

```bash
ip neighbour
```

- Active/Désactive une interface :

```bash
ip link set interface up/down
```

- Ajoute/Supprime une adresse ip à une interface :

```bash
ip addr add/del ip/mask dev interface
```

- Ajoute une route par défaut :

```bash
ip route add default via ip dev interface
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | *: mention subcommands in FR translations (#6823) | 2021-10-06T22:45:59 | [b0e0a6e58cfb](https://github.com/tldr-pages/tldr/commit/b0e0a6e58cfbff6cb7041a4d37b1b46ddac79941)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix more information text in French translation (#5773) | 2021-04-25T07:11:35 | [12915f11c283](https://github.com/tldr-pages/tldr/commit/12915f11c2836fedc735ee779e57fd1d8a149cb8)
[Matthew Peveler](mailto:matt.peveler@gmail.com) | ip: fix example formatting (#5761) | 2021-04-15T19:47:57 | [99153a860d4a](https://github.com/tldr-pages/tldr/commit/99153a860d4a365cbc0fba5522646ec22a60bffb)
[Patrice Denis](mailto:patrice.denis@gmail.com) | at, ifdown, ifup, ip-address, ip: add French translation (#5505) | 2021-03-27T12:51:16 | [170f5f9ebcfc](https://github.com/tldr-pages/tldr/commit/170f5f9ebcfca1427d1f70e33387134c09795552)

