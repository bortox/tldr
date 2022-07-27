---
author: ['Andreia Bohner']
date: 1658135504
title: "bc, TLDR Pages"
description: "bc, Linguagem e calculadora com precisão arbitrária."
categories: "osx"
---
> Veja também: `dc`.

> Mais informações: <https://manned.org/man/freebsd-13.0/bc.1>.

- Iniciar uma sessão interativa:

```bash
bc
```

- Iniciar uma sessão interativa com a biblioteca matemática padrão habilitada:

```bash
bc --mathlib
```

- Calcular uma expressão:

```bash
bc --expression='5 / 3'
```

- Executar um script:

```bash
bc caminho/para/script.bc
```

- Calcular uma expressão com a escala especificada:

```bash
bc --expression='scale = 10; 5 / 3'
```

- Calcular uma função sine/cosine/arctangent/natural logarithm/exponential usando `mathlib`:

```bash
bc --mathlib --expression='s|c|a|l|e(1)'
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Andreia Bohner](mailto:andreiabohner@gmail.com) | bc: add pt_BR translation | 2022-07-18T11:11:44 | [d5219cafb8df](https://github.com/tldr-pages/tldr/commit/d5219cafb8df8b8b7b442e62e9d17b8dd4a71fea)

