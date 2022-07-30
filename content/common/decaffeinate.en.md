---
author: ['Jan T. Sott', 'pxgamer', 'Lucas Gabriel Schneider']
date: 1612112718
title: "decaffeinate"
description: "decaffeinate, Move your CoffeeScript source to modern JavaScript."
categories: "common"
---
> More information: <https://decaffeinate-project.org>.

- Convert a CoffeeScript file to JavaScript:

```bash
decaffeinate path/to/file.coffee
```

- Convert a CoffeeScript v2 file to JavaScript:

```bash
decaffeinate --use-cs2 path/to/file.coffee
```

- Convert require and `module.exports` to import and export:

```bash
decaffeinate --use-js-modules path/to/file.coffee
```

- Convert a CoffeeScript, allowing named exports:

```bash
decaffeinate --loose-js-modules path/to/file.coffee
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | decaffeinate: add link to homepage | 2019-06-09T06:54:24 | [dcc3d04301bd](https://github.com/tldr-pages/tldr/commit/dcc3d04301bd4ce19b1b3f72b0e14af559b1d7ab)
[Jan T. Sott](mailto:jan@idleberg.com) | decaffeinate: add page (#2228) | 2018-07-31T21:33:42 | [61ed846787ae](https://github.com/tldr-pages/tldr/commit/61ed846787ae605278046803e2de66099267e7c6)

