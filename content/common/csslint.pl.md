---
author: ['Michal']
date: 1587299476
title: "csslint"
description: "csslint, Linter dla kodu CSS."
categories: "common"
---
> Więcej informacji: <https://github.com/CSSLint/csslint/wiki/Command-line-interface>.

- Lintowanie pojedynczego pliku CSS:

```bash
csslint plik.css
```

- Lintowanie wiele plików CSS:

```bash
csslint plik1.css plik2.css plik3.css
```

- Wymień wszystkie możliwe reguły stylu:

```bash
csslint --list-rules
```

- Określ pewne reguły jako błędy (które powodują niezerowy kod wyjścia):

```bash
csslint --errors=bledy,universal-selector,imports plik.css
```

- Określ pewne reguły jako ostrzeżenia:

```bash
csslint --warnings=box-sizing,selector-max,floats plik.css
```

- Określ pewne reguły, które będą całkowicie ignorowane:

```bash
csslint --ignore=ids,rules-count,shorthand plik.css
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Michal](mailto:mich.biesiada@gmail.com) | update csslint updated | 2020-04-19T14:31:16 | [0d7cf09c0b92](https://github.com/tldr-pages/tldr/commit/0d7cf09c0b92103b882f11d1cd9e8d5ab0c8b40d)
[Michal](mailto:mich.biesiada@gmail.com) | update csslint updated | 2020-04-19T14:31:16 | [35a011c7f74d](https://github.com/tldr-pages/tldr/commit/35a011c7f74d1c120ba32198a48e979827816ba7)
[Michal](mailto:mich.biesiada@gmail.com) | create csslint.md initial | 2020-04-19T14:31:16 | [67e8c7552c16](https://github.com/tldr-pages/tldr/commit/67e8c7552c163e1c474592cc9c2ebcfe7fc305f5)

