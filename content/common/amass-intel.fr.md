---
author: ['Nicolas Hansse']
date: 1658041505
title: "amass intel"
description: "amass intel, Collecte des renseignements open source sur une organisation comme les noms de domaines racine et les ASNs."
categories: "common"
---
> Plus d'informations : <https://github.com/OWASP/Amass/blob/master/doc/user_guide.md#the-intel-subcommand>.

- Recherche les domaines racines inclus dans une plage d'adresse IP :

```bash
amass intel -addr 192.168.0.1-254
```

- Utilise les méthodes de reconnaissance active :

```bash
amass intel -active -addr 192.168.0.1-254
```

- Recherche les noms de domaines racines reliés à un domaine :

```bash
amass intel -whois -d nom_de_domaine
```

- Recherche les ASNs qui correspondent à une organisation :

```bash
amass intel -org nom_de_l_organisation
```

- Recherche les domaines racines qui correspondent à un ASN :

```bash
amass intel -asn asn
```

- Sauvegarde les résultats dans un fichier texte :

```bash
amass intel -o fichier_de_sortie -whois -d nom_de_domaine
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | amass-intel, amass-track, amass-viz: add French translation (#8210) | 2022-07-17T09:05:05 | [3ce8ac7de035](https://github.com/tldr-pages/tldr/commit/3ce8ac7de035f7f1be6e9285df49bbe28b35ad56)

