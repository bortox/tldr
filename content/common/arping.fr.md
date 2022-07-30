---
author: ['Nicolas Hansse']
date: 1659170949
title: "arping"
description: "arping, Découvre et sonde des hôtes dans un réseau en utilisant le protocol ARP."
categories: "common"
---
> Très utile pour la découverte d'adresse MAC.

> Plus d'informations : <https://github.com/ThomasHabets/arping>.

- Ping un hôte par paquets de requête ARP :

```bash
arping ip_hôte
```

- Ping un hôte sur une interface spécifique :

```bash
arping -I interface ip_hôte
```

- Ping un hôte et arrête à la première réponse :

```bash
arping -f ip_hôte
```

- Ping un hôte un certain nombre de fois :

```bash
arping -c nombre_d_appel ip_hôte
```

- Diffuse les paquets de requête ARP pour mettre à hour les caches ARP voisin :

```bash
arping -U ip_à_diffuser
```

- Détecte les adresses IP dupliquées dans le réseau en envoyant les requêtes ARP avec une expiration de 3 secondes :

```bash
arping -D -w 3 ip_à_vérifier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | arping, asar: add French translation (#8263) | 2022-07-30T10:49:09 | [a443185d894a](https://github.com/tldr-pages/tldr/commit/a443185d894a61d8354b592125dcf14b83c05da1)

