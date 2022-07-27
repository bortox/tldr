---
author: ['Miles Glapa-Grossklag', 'Victorhck', 'Axel Navarro']
date: 1630283910
title: "figlet, TLDR Pages"
description: "figlet, Genera encabezados usando caracteres ASCII desde la entrada del usuario."
categories: "common"
---
> Véase también `showfigfonts`.

> Más información: <http://www.figlet.org/figlet-man.html>.

- Genera el encabezado directamente introduciendo el texto:

```bash
figlet texto_de_entrada
```

- Usa un archivo de fuente personalizada:

```bash
figlet texto_de_entrada -f ruta/al/archivo_de_fuente.flf
```

- Use una fuente del directorio predeterminado (la extensión puede ser omitida):

```bash
figlet texto_de_entrada -f archivo_de_fuente
```

- Redirige la salida de un comando hacia figlet:

```bash
comando | figlet
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | figlet: fix language mixup (#6438) | 2021-08-30T02:38:30 | [ff4f42a5d916](https://github.com/tldr-pages/tldr/commit/ff4f42a5d916056d4c2d30406e2300ca1c981ba5)
[Axel Navarro](mailto:navarroaxel@gmail.com) | showfigfonts: add page (#6217) | 2021-07-14T21:31:29 | [d5f22be32686](https://github.com/tldr-pages/tldr/commit/d5f22be326869ae289a49499fba5d5a11422bc96)
[Victorhck](mailto:victorhck@mailbox.org) | bc, figlet: add Spanish translation (#6208) | 2021-07-10T00:32:40 | [2219faa37c06](https://github.com/tldr-pages/tldr/commit/2219faa37c062ec1772cf79720c8dc6cdaa12726)

