---
author: ['Axel Navarro', 'Iván', 'marchersimon', 'Lucas Gabriel Schneider']
date: 1633112881
title: "cpdf"
description: "cpdf, Interfaz de línea de comandos para manipular documentos PDF existentes de diferentes maneras."
categories: "common"
---
> Más información: <https://www.coherentpdf.com/cpdfmanual/cpdfmanual.html>.

- Selecciona las páginas 1, 2, 3 y 6 del documento fuente y escribirlas en el documento objetivo:

```bash
cpdf ruta/al/documento_fuente.pdf 1-3,6 -o ruta/al/documento_objetivo.pdf
```

- Fusiona dos documentos en uno nuevo:

```bash
cpdf -merge ruta/al/documento_fuente_uno.pdf ruta/al/documento_fuente_dos.pdf -o ruta/al/documento_objetivo.pdf
```

- Muestra los marcadores del documento:

```bash
cpdf -list-bookmarks ruta/al/documento.pdf
```

- Divide un documento en trozos de diez páginas, escribiendo `fragmento001.pdf`, `fragmento002.pdf`, etc:

```bash
cpdf -split ruta/al/documento.pdf -o ruta/al/fragmento%%%.pdf -chunk 10
```

- Encripta un documento utilizando encriptado 128bit y establece `fred` como la contraseña del propietario y `joe` como la contraseña de usuario:

```bash
cpdf -encrypt 128bit fred joe ruta/al/documento_fuente.pdf -o ruta/al/documento_encriptado.pdf
```

- Desencripta un documento utilizando la contraseña del propietario (`fred`):

```bash
cpdf -decrypt ruta/al/documento_encriptado.pdf owner=fred -o ruta/al/documento_desencriptado.pdf
```

- Muestra las anotaciones de un documento:

```bash
cpdf -list-annotations ruta/al/documento.pdf
```

- Crea un nuevo documento, con metadatos, a partir de uno que ya existe:

```bash
cpdf -set-metadata ruta/de/los/metadatos.xml ruta/al/documento_fuente.pdf -o ruta/al/documento_objetivo.pdf
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Axel Navarro](mailto:navarroaxel@gmail.com) | cpdf, git-*: fix path to Spanish translation (#5440) | 2021-03-14T14:30:23 | [b80a854c4a2e](https://github.com/tldr-pages/tldr/commit/b80a854c4a2e8973e26977b8373c5c46c8a55c70)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Iván](mailto:ivan@ivanhercaz.com) | cpdf: add Spanish translation (#3717) | 2020-01-04T00:36:54 | [d088cd24be90](https://github.com/tldr-pages/tldr/commit/d088cd24be90db88ef6e2933e6e8c2c61f28ea90)

