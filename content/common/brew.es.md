---
author: ['Axel Navarro']
date: 1631111627
title: "brew"
description: "brew, Administrador de paquetes para macOS y Linux."
categories: "common"
---
> Más información: <https://brew.sh>.

- Instala la última versión estable de una fórmula (usar `--devel` para versiones de desarrollo):

```bash
brew install formula
```

- Lista todas las fórmulas y casks instaladas:

```bash
brew list
```

- Actualiza una fórmula o cask instalada (si no se indica ninguna, todas las fórmulas/casks se actualizan):

```bash
brew upgrade formula
```

- Trae la versión más reciente de Homebrew y todas sus fórmulas y casks desde el repositorio fuente de Homebrew:

```bash
brew update
```

- Muestra las fórmulas y casks que tienen una versión más reciente disponible:

```bash
brew outdated
```

- Busca fórmulas (por ej. paquetes) y casks (por ej. paquetes nativos) disponibles:

```bash
brew search texto
```

- Muestra la información de una fórmula o un cask (versión, ruta de instalación, dependencias, etc.):

```bash
brew info formula
```

- Revisa la instalación local de Homebrew en busca de problemas potenciales:

```bash
brew doctor
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | brew: sync Spanish translation (#6490) | 2021-09-08T16:33:47 | [50144e4a3075](https://github.com/tldr-pages/tldr/commit/50144e4a30759d5e52f16c8fc956231af2cb158d)

