---
author: ['Axel Navarro', 'Gonzalo Contreras Aso']
date: 1616858375
title: "nms"
description: "nms, Herramienta de línea de comandos que recrea el famoso efecto de desencriptado de datos de la película Sneakers (1992)."
categories: "common"
---
> Más información: <https://github.com/bartobri/no-more-secrets>.

- Desencripta el texto tras presionar una tecla:

```bash
echo "Hola, Mundo!" | nms
```

- Desencripta la salida inmediatamente, sin esperar a que una tecla sea pulsada:

```bash
ls -la | nms -a
```

- Desencripta el contenido de un archivo, especificando el color de la salida:

```bash
cat ruta/al/archivo | nms -a -f blue|white|yellow|black|magenta|green|red
```

- Limpia la pantalla antes de desencriptar:

```bash
comando | nms -a -c
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | nms: fix Spanish translation | 2021-03-27T16:19:35 | [a1ab9cc0d5e9](https://github.com/tldr-pages/tldr/commit/a1ab9cc0d5e9e456946b76b312d6b719a250005b)
[Gonzalo Contreras Aso](mailto:61254163+goznalo-git@users.noreply.github.com) | nms: add page (#5483) | 2021-03-25T22:55:28 | [e7421cee1358](https://github.com/tldr-pages/tldr/commit/e7421cee1358e1c59ead1e1e3b9f0922f4dd736b)

