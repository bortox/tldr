---
author: ['qontinuum-dev']
date: 1636097238
title: "apk, TLDR Pages"
description: "apk, Gestionnaire de paquet d'Alpine Linux."
categories: "linux"
---
> Plus d'informations : <https://wiki.alpinelinux.org/wiki/Alpine_Linux_package_management>.

- Mets à jour les indexes de tous les dépôts distants :

```bash
apk update
```

- Installe un nouveau paquet :

```bash
apk add paquet
```

- Désinstalle un paquet :

```bash
apk del paquet
```

- Essaye de réparer un paquet ou de mettre à jour un paquet sans ses dépendances :

```bash
apk fix paquet
```

- Recherche des paquets à partir d'un mot-clé :

```bash
apk search mot_cle
```

- Obtiens des information à propos d'un paquet précis :

```bash
apk info paquet
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[qontinuum-dev](mailto:79641156+qontinuum-dev@users.noreply.github.com) | apk: add French translation (#7047) | 2021-11-05T08:27:18 | [bfb791c43afd](https://github.com/tldr-pages/tldr/commit/bfb791c43afd6392e1c40c7931ff1abe5f3b4950)

