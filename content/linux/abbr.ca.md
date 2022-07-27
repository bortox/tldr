---
author: ['Seifer23']
date: 1644117941
title: "abbr, TLDR Pages"
description: "abbr, Gestiona abreviatures per la shell fish."
categories: "linux"
---
> Les paraules definides per l'usuari es reemplacen per expresions llarges en introduïr-les.

> Més informació: <https://fishshell.com/docs/current/cmds/abbr.html>.

- Afegeix una nova abreviatura:

```bash
abbr --add nom_abreviatura comandament arguments
```

- Canvia el nom d'una abreviatura existent:

```bash
abbr --rename antic_nom nou_nom
```

- Esborra una abreviatura existent:

```bash
abbr --erase nom_abreviatura
```

- Importa les abreviatures definides en un altre host per SSH:

```bash
ssh nom_host abbr --show | source
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

