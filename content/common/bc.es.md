---
author: ['marchersimon', 'Victorhck']
date: 1659075216
title: "bc"
description: "bc, Un lenguaje de calculadora de precisión arbitraria."
categories: "common"
---
> Más información: <https://manned.org/man/bc.1>.

- Inicia `bc` en el modo interactivo utilizando la biblioteca matemática estándar:

```bash
bc -l
```

- Calcula el resultado de una expresión:

```bash
bc <<< "(1 + 2) * 2 ^ 2"
```

- Calcula el resultado de una expresión y fuerza a que el resultado tenga 10 cifras decimales:

```bash
bc <<< "scale=10; 5 / 3"
```

- Calcula el resultado de una expresión con el seno y coseno utilizando `mathlib`:

```bash
bc -l <<< "s(1) + c(1)"
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Victorhck](mailto:victorhck@mailbox.org) | bc, figlet: add Spanish translation (#6208) | 2021-07-10T00:32:40 | [2219faa37c06](https://github.com/tldr-pages/tldr/commit/2219faa37c062ec1772cf79720c8dc6cdaa12726)

