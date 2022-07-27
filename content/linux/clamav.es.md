---
author: ['Ignacio Mattos', 'Andoni Alonso']
date: 1607017815
title: "clamav, TLDR Pages"
description: "clamav, Antivirus de código abierto."
categories: "linux"
---
> Diseñado especialment para escanear correos electrónicos, pero puede ser usado en otros contextos.

> Más información: <https://www.clamav.net>.

- Actualiza definiciones de virus:

```bash
freshclam
```

- Escanea un archivo en busca de virus:

```bash
clamscan ruta/al/archivo
```

- Escanea directorios recursivamente y mostrar los archivos infectados:

```bash
clamscan --recursive --infected ruta/al/directorio
```

- Escanea directorios recursivamente y poner los archivos infectados en cuarentena:

```bash
clamscan --recursive --move=directorio
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)
[Andoni Alonso](mailto:14891798+andoniaf@users.noreply.github.com) | clamav, cmus: add Spanish translation (#4698) | 2020-10-19T18:25:49 | [a7f895883dfa](https://github.com/tldr-pages/tldr/commit/a7f895883dfacab05e4e4c3c1492de04252d5ed3)

