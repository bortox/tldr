---
author: ['Simao Ferreira']
date: 1642277486
title: "xrdb"
description: "xrdb, Utilitário de base de dados de recursos para servidor X window em sistemas tipo Unix."
categories: "linux"
---
> Mais informações: <https://www.x.org/releases/X11R7.7/doc/man/man1/xrdb.1.xhtml>.

- Iniciar `xrdb` em modo interactivo:

```bash
xrdb
```

- Carregar valores (p. ex. regras de estilo) de um ficheiro de recursos:

```bash
xrdb -load ~/.Xresources
```

- Consultar base de dados de recursos e mostrar estado actual dos recursos:

```bash
xrdb -query
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Simao Ferreira](mailto:24299428+simao-ferreira@users.noreply.github.com) | xrdb: add pt_PT translation (#7654) | 2022-01-15T21:11:26 | [5cc2a5ca0856](https://github.com/tldr-pages/tldr/commit/5cc2a5ca0856e517e7c219b1adabe2568f089605)

