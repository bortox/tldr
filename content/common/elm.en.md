---
author: ['mira01', 'pxgamer', 'Ruben Lie King', 'Lucas Gabriel Schneider', 'bl-ue']
date: 1621541621
title: "elm, TLDR Pages"
description: "elm, Compile and run Elm source files."
categories: "common"
---
> More information: <https://elm-lang.org>.

- Initialize an Elm project, generates an elm.json file:

```bash
elm init
```

- Start interactive Elm shell:

```bash
elm repl
```

- Compile an Elm file, output the result to an `index.html` file:

```bash
elm make source
```

- Compile an Elm file, output the result to a JavaScript file:

```bash
elm make source --output=destination.js
```

- Start local web server that compiles Elm files on page load:

```bash
elm reactor
```

- Install Elm package from https://package.elm-lang.org:

```bash
elm install author/package
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | elm: add link to homepage | 2019-06-09T06:54:24 | [4da696e4ba83](https://github.com/tldr-pages/tldr/commit/4da696e4ba837dc8eb6a673232aafad5875c6d87)
[Ruben Lie King](mailto:hello@rubenlieking.com) | elm: update page, add elm make example (#2683) * elm: update page | 2019-01-07T16:10:29 | [7faabae907be](https://github.com/tldr-pages/tldr/commit/7faabae907bece858cfd526fca47532d558ec66a)
[mira01](mailto:miracech@email.cz) | elm: add page (#2365) | 2018-10-03T11:31:36 | [bc6d1c1cb99b](https://github.com/tldr-pages/tldr/commit/bc6d1c1cb99b390e0e5ed889fd274a8fe659c7ca)

