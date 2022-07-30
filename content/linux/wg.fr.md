---
author: ['marcan2020', 'Muhammad Falak R Wani', 'lincc']
date: 1643487459
title: "wg"
description: "wg, Gestion de la configuration des interfaces WireGuard."
categories: "linux"
---
> Plus d'informations : <https://www.wireguard.com/quickstart/>.

- Vérifier l'état des interfaces actuellement actives :

```bash
wg
```

- Générer une clé privée :

```bash
wg genkey
```

- Générer une clé publique à partir d'une clé privée :

```bash
wg pubkey < chemin/vers/clé_privée > chemin/vers/clé_publique
```

- Générer une clé publique et privée :

```bash
wg genkey | tee chemin/vers/clé_privée | wg pubkey > chemin/vers/clé_publique
```

- Afficher la configuration actuelle d'une interface wireguard :

```bash
wg showconf wg0
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | wg: add example to show current configuration of an interface (#7594) Signed-off-by: Muhammad Falak R Wani <falakreyaz@gmail.com> | 2022-01-03T11:09:51 | [722304b2162d](https://github.com/tldr-pages/tldr/commit/722304b2162d869d36c2d4b494944ff9d896dc89)
[marcan2020](mailto:marcan2020@gmail.com) | wg: refresh and add French translation (#6687) | 2021-10-14T05:24:01 | [50fad57fd18c](https://github.com/tldr-pages/tldr/commit/50fad57fd18cfb3efc92d41c69d66e8a649e382e)

