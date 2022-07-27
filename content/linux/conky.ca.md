---
author: ['Seifer23']
date: 1644117941
title: "conky, TLDR Pages"
description: "conky, Monitor de sistema lleuger per X."
categories: "linux"
---
> Més informació: <https://github.com/brndnmtthws/conky>.

- Executa amb la configuració per defecte:

```bash
conky
```

- Crea una nova configuració per defecte:

```bash
conky -C > ~/.conkyrc
```

- Executa conky amb un arxiu de configuració concret:

```bash
conky -c ruta/a/la/configuració
```

- Executa en segon pla (*daemon*):

```bash
conky -d
```

- Posiciona conky en l'escriptori:

```bash
conky -a {top,bottom,middle}_{left,right,middle}
```

- Pausa de 5 segons al iniciar abans d'executar-lo:

```bash
conky -p 5
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

