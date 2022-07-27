---
author: ['Nicolas Kosinski', 'Patrice Denis', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1633592259
title: "ip address, TLDR Pages"
description: "ip address, Sous-commande de gestion des adresses IP."
categories: "linux"
---
> Plus d'informations : <https://manned.org/ip-address>.

- Liste les interfaces réseau et leurs adresses IP associées :

```bash
ip address
```

- Filtre pour n'afficher que les interfaces réseau actives :

```bash
ip address show up
```

- Affiche les informations relatives à une interface réseau spécifique :

```bash
ip address show dev eth0
```

- Ajoute une adresse IP à une interface réseau :

```bash
ip address add ip_address dev eth0
```

- Supprimer une adresse réseau d'une interface réseau :

```bash
ip address delete ip_address dev eth0
```

- Supprime l'ensemble des adresses IP sur une portée donnée (scope) depuis une interface réseau :

```bash
ip address flush dev eth0 scope global|host|link
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix more information text in French translation (#5773) | 2021-04-25T07:11:35 | [12915f11c283](https://github.com/tldr-pages/tldr/commit/12915f11c2836fedc735ee779e57fd1d8a149cb8)
[Patrice Denis](mailto:patrice.denis@gmail.com) | at, ifdown, ifup, ip-address, ip: add French translation (#5505) | 2021-03-27T12:51:16 | [170f5f9ebcfc](https://github.com/tldr-pages/tldr/commit/170f5f9ebcfca1427d1f70e33387134c09795552)

