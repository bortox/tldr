---
author: ['Ignacio Mattos']
date: 1607017815
title: "dotnet publish"
description: "dotnet publish, Publica una aplicación .NET y sus dependencias en una carpeta para la implementación en un sistema de hospedaje."
categories: "common"
---
> Más información: <https://docs.microsoft.com/dotnet/core/tools/dotnet-publish>.

- Compila un proyecto .NET en modo de lanzamiento:

```bash
dotnet publish --configuration Release ruta/al/archivo_del_proyecto
```

- Publica el entorno de ejecución de .NET Core con la aplicación para un entorno de ejecución específico:

```bash
dotnet publish --self-contained true --runtime identificador_del_entorno_en_tiempo_de_ejecución ruta/al/archivo_del_proyecto
```

- Empaqueta la aplicación en un archivo ejecutable unico de una plataforma específica:

```bash
dotnet publish --runtime identificador_del_entorno_en_tiempo_de_ejecucución -p:PublishSingleFile=true ruta/al/archivo_del_proyecto
```

- Recorta las bibliotecas no usadas para reducir el tamaño de la aplicación:

```bash
dotnet publish --self-contained true --runtime identificador_del_entorno_de_tiempo_de_ejecución -p:PublishTrimmed=true ruta/al/archivo_del_proyecto
```

- Compila un proyecto .NET sin restaurar las dependencias:

```bash
dotnet publish --no-restore ruta/al/archivo_del_proyecto
```

- Especifica el directorio de salida:

```bash
dotnet publish --output ruta/al/directorio ruta/al/archivo_del_proyecto
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)

