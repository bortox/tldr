---
author: ['bl-ue', 'Ignacio Mattos']
date: 1615232246
title: "dotnet restore"
description: "dotnet restore, Restarua las dependencias y herramientas de un proyecto .NET."
categories: "common"
---
> Más información: <https://docs.microsoft.com/dotnet/core/tools/dotnet-restore>.

- Restaura dependencias para un proyecto o solución .NET en el directorio actual:

```bash
dotnet restore
```

- Restaura dependencias para un proyecto o solución .NET en una ubicación específica:

```bash
dotnet restore ruta/al/proyecto_o_solución
```

- Restaura depedencias sin almacenar las solicitudes HTTP en caché:

```bash
dotnet restore --no-cache
```

- Obliga a todas las dependencias a ser resueltas incluso si la última restauración fue exitosa:

```bash
dotnet restore --force
```

- Restaura dependencias usando los orígenes con error como advertencias:

```bash
dotnet restore --ignore-failed-sources
```

- Restaura dependencias con un nivel específico de verbosidad:

```bash
dotnet restore --verbosity quiet|minimal|normal|detailed|diagnostic
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Spanish pages: fix (valid) tldr-lint errors (#5364) | 2021-03-08T20:37:26 | [4d28344d0f69](https://github.com/tldr-pages/tldr/commit/4d28344d0f69eca05bef1c0b26c2839240dd4e1f)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)

