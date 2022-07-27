---
author: ['Victorhck']
date: 1625869960
title: "bc, TLDR Pages"
description: "bc, Un lenguaje de calculadora de precisión arbitraria."
categories: "common"
---
> Más información: <https://manned.org/bc>.

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
[Victorhck](mailto:victorhck@mailbox.org) | bc, figlet: add Spanish translation (#6208) | 2021-07-10T00:32:40 | [2219faa37c06](https://github.com/tldr-pages/tldr/commit/2219faa37c062ec1772cf79720c8dc6cdaa12726)

