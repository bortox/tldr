---
author: ['bl-ue', 'Víctor Fernández', 'Nicolas Kosinski']
date: 1626957133
title: "gradle"
description: "gradle, Gradle es un sistema de código abierto para automatizar la compilación de proyectos."
categories: "common"
---
> Más información: <https://gradle.org>.

- Compila un proyecto:

```bash
gradle build
```

- Excluye la tarea *test*:

```bash
gradle build -x test
```

- Ejecuta en modo offline para prevenir que Gradle acceda a la red durante una compilación:

```bash
gradle build --offline
```

- Limpia el directorio de compilación:

```bash
gradle clean
```

- Compila un paquete Android (APK) en modo lanzamiento:

```bash
gradle assembleRelease
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | gradle: edit assembleRelease example to show Android Studio specificity (#6194) 'assembleDebug' and 'assembleRelease' tasks are [...] | 2021-07-22T14:32:13 | [1c050a6e38c5](https://github.com/tldr-pages/tldr/commit/1c050a6e38c5efc26b271409f6892c5013dfce40)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Spanish pages: fix (valid) tldr-lint errors (#5364) | 2021-03-08T20:37:26 | [4d28344d0f69](https://github.com/tldr-pages/tldr/commit/4d28344d0f69eca05bef1c0b26c2839240dd4e1f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Víctor Fernández](mailto:vfrico@gmail.com) | gradle: Add spanish translation (#4728) | 2020-10-19T19:16:16 | [505f8016f5b1](https://github.com/tldr-pages/tldr/commit/505f8016f5b1e4aa8110fb3c895df5c5a7bfb1f2)

