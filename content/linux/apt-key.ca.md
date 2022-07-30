---
author: ['Seifer23']
date: 1644117941
title: "apt-key"
description: "apt-key, Eina de gestió de claus per al Gestor de Paquets APT (APT Package Manager) en Debian i Ubuntu."
categories: "linux"
---
> Nota: `apt-key` és obsolet (excepte l'ús de `apt-key del` en scrits de mantenidor).

> Més informació: <https://manpages.debian.org/latest/apt/apt-key.8.html>.

- Mostra les claus de confiança:

```bash
apt-key list
```

- Afegeix una clau al magatzem de claus de confiança:

```bash
apt-key add arxiu_clau_pública.asc
```

- Borra una clau del magatzem de claus de confiança:

```bash
apt-key del id_clau
```

- Afegir una clau remota al magatzem de claus de confiança:

```bash
wget -qO - https://host.tld/archiu.clau | apt-key add -
```

- Afegir una clau d'un servidor de claus amb l'identificador de la clau:

```bash
apt-key adv --keyserver pgp.mit.edu --recv id_clau
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

