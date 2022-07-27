---
author: ['Iván', 'Ignacio Mattos', 'bl-ue']
date: 1615232246
title: "conky, TLDR Pages"
description: "conky, Monitor de sistema ligero para X."
categories: "linux"
---
> Más información: <https://github.com/brndnmtthws/conky>.

- Ejecuta con la configuración por defecto:

```bash
conky
```

- Crea una nueva configuración por defecto:

```bash
conky -C > ~/.conkyrc
```

- Ejecuta conky con un archivo de configuración concreto:

```bash
conky -c ruta/a/la/configuración
```

- Ejecuta en segundo plano (*daemon*):

```bash
conky -d
```

- Alinea conky en el escritorio:

```bash
conky -a {arriba,abajo,en_medio}_{izquierda,derecha,en_medio}
```

- Pausa de 5 segundos al inciar antes de ejecutarlo:

```bash
conky -p 5
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Spanish pages: fix (valid) tldr-lint errors (#5364) | 2021-03-08T20:37:26 | [4d28344d0f69](https://github.com/tldr-pages/tldr/commit/4d28344d0f69eca05bef1c0b26c2839240dd4e1f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)
[Iván](mailto:ivan@ivanhercaz.com) | conky: add Spanish translation (#3683) | 2019-12-27T23:12:43 | [c98208430271](https://github.com/tldr-pages/tldr/commit/c9820843027108d66c5d72cde1dd68405b5f7d9b)

