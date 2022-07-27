---
author: ['Iván', 'Dario Vladović', 'bl-ue', 'marchersimon']
date: 1617292466
title: "chmod, TLDR Pages"
description: "chmod, Cambiar los permisos de acceso de un archivo o directorio."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/chmod>.

- Otorga al [u]suario que es propietario del archivo permiso para [x] ejecutarlo:

```bash
chmod u+x archivo
```

- Otorga al usuario derechos para leer (r) y escribir (w) un archivo o directorio:

```bash
chmod u+rw archivo_o_directorio
```

- Elimina los derechos de ejecución del [g]rupo:

```bash
chmod g-x archivo
```

- Otorga a todos los usuarios (a) derechos para leer y ejecutar:

```bash
chmod a+rx archivo
```

- Otorga a [o]tros (que no están en el grupo del propietario) los mismos derechos que los del grupo:

```bash
chmod o=g archivo
```

- Otorga al [g]rupo y a [o]tros el derecho para escribir (w) un directorio y su contenido:

```bash
chmod -R g+w,o+w directorio
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chmod: change more information link (#5547) | 2021-03-29T22:28:18 | [db38dff0e9db](https://github.com/tldr-pages/tldr/commit/db38dff0e9db1d880e7406df340d16509470fbbb)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Iván](mailto:ivan@ivanhercaz.com) | chmod: add Spanish translation (#3705) | 2019-12-31T19:12:33 | [2e0ae5c87b35](https://github.com/tldr-pages/tldr/commit/2e0ae5c87b35fe8a95a60168e71b5f3099f33724)

