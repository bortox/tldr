---
author: ['Seifer23']
date: 1644117941
title: "a2query"
description: "a2query, Recupera la configuració del temps d'execució d'Apache en sistemes operatius basats en Debian."
categories: "linux"
---
> Més informació: <https://manpages.debian.org/latest/apache2/a2query.html>.

- Llista mòduls Apache activats:

```bash
sudo a2query -m
```

- Comprova si un mòdul específic està instal·lat:

```bash
sudo a2query -m nom_mòdul
```

- Llista els hosts virtuals activats:

```bash
sudo a2query -s
```

- Mostra el mòdul de processament múltiple:

```bash
sudo a2query -M
```

- Mostra la versió d'Apache:

```bash
sudo a2query -v
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

