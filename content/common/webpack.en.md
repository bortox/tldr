---
author: ['Agniva De Sarker', 'Owen Voke', 'Lucas Gabriel Schneider', 'Marco Bonelli', 'Seth Falco']
date: 1629050349
title: "webpack"
description: "webpack, Bundle a web project's js files and other assets into a single output file."
categories: "common"
---
> More information: <https://webpack.js.org>.

- Create a single output file from an entry point file:

```bash
webpack app.js bundle.js
```

- Load CSS files too from the JavaScript file (this uses the CSS loader for `.css` files):

```bash
webpack app.js bundle.js --module-bind 'css=css'
```

- Pass a config file (with e.g. the entry script and the output filename) and show compilation progress:

```bash
webpack --config webpack.config.js --progress
```

- Automatically recompile on changes to project files:

```bash
webpack --watch app.js bundle.js
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | webpack: add page (#940) | 2016-07-08T11:40:36 | [f080073fad62](https://github.com/tldr-pages/tldr/commit/f080073fad627dabab934e8498c0851884521617)

