---
author: ['Ignacio Mattos']
date: 1607017815
title: "dotnet build, TLDR Pages"
description: "dotnet build, Compila una aplicación .NET y sus dependencias."
categories: "common"
---
> Más información: <https://docs.microsoft.com/dotnet/core/tools/dotnet-build>.

- Compila el proyecto o solución en el directorio actual:

```bash
dotnet build
```

- Compila un proyecto o solución .NET en el modo de depuración:

```bash
dotnet build ruta/al/proyecto_o_solución
```

- Compila en modo de lanzamiento:

```bash
dotnet build --configuration Release
```

- Compila sin restaurar las dependencias:

```bash
dotnet build --no-restore
```

- Compila con un nivel específico de verbosidad:

```bash
dotnet build --verbosity quiet|minimal|normal|detailed|diagnostic
```

- Compila para un tiempo de ejecución específico:

```bash
dotnet build --runtime identificador_del_tiempo_de_ejecución
```

- Especifica el directorio de salida:

```bash
dotnet build --output ruta/al/directorio
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)

