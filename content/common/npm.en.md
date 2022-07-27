---
author: ['Waldir Pimenta', 'Artem Szubowicz', 'Seth Falco', 'Leandro Ostera', 'Marco Bonelli', 'Livio Bieri', 'Ruben Vereecken', 'Agniva De Sarker', 'Son A. Pham', 'Igor Shubovych', 'Kyle Warneck', 'Raymond Douglas', 'Nicolas Kosinski', 'rprieto', 'Lucas Gabriel Schneider', 'Axel Navarro', 'Starbeamrainbowlabs']
date: 1643827401
title: "npm, TLDR Pages"
description: "npm, JavaScript and Node.js package manager."
categories: "common"
---
> Manage Node.js projects and their module dependencies.

> More information: <https://www.npmjs.com>.

- Interactively create a `package.json` file:

```bash
npm init
```

- Download all the packages listed as dependencies in package.json:

```bash
npm install
```

- Download a specific version of a package and add it to the list of dependencies in `package.json`:

```bash
npm install module_name@version
```

- Download a package and add it to the list of dev dependencies in `package.json`:

```bash
npm install module_name --save-dev
```

- Download a package and install it globally:

```bash
npm install --global module_name
```

- Uninstall a package and remove it from the list of dependencies in `package.json`:

```bash
npm uninstall module_name
```

- Print a tree of locally installed dependencies:

```bash
npm list
```

- List top-level globally installed modules:

```bash
npm list --global --depth=0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | *: use author link instead of npm package (#7730) | 2022-02-02T19:43:21 | [c2c16f61acbd](https://github.com/tldr-pages/tldr/commit/c2c16f61acbdca1933961fbbc20a80bdae76ece5)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | npm: use long argument --global (#5880) | 2021-05-04T09:26:22 | [1fe05c4e59dd](https://github.com/tldr-pages/tldr/commit/1fe05c4e59ddbb8aebbd121f692cd3b743087724)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Kyle Warneck](mailto:warneck@adobe.com) | npm: revised description of npm list | 2019-03-13T04:42:11 | [2c6e7f7c20c5](https://github.com/tldr-pages/tldr/commit/2c6e7f7c20c5636b180dac112c7e3df36c9ecc8d)
[Kyle Warneck](mailto:warneck@adobe.com) | npm: remove unncessary --save flag. simplify descriptions removes unnecssary --save flag (added by default in npm > 5). Adds an [...] | 2019-03-13T04:42:11 | [5f5cd8759e30](https://github.com/tldr-pages/tldr/commit/5f5cd8759e30df55f6aa9df1080adb7c4f786d61)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | fix minor grammatical issue | 2017-11-23T07:11:06 | [88289e54be0f](https://github.com/tldr-pages/tldr/commit/88289e54be0ff2c11fa72715bab86d04960ef7bf)
[Raymond Douglas](mailto:raymondjdouglas@gmail.com) | npm.md: additional module listing use case Made changes per suggestions by agnivade. | 2017-11-23T07:06:43 | [5b9848dc644d](https://github.com/tldr-pages/tldr/commit/5b9848dc644daedd1a2943a8ad168d8c0a751fc7)
[Raymond Douglas](mailto:raymondjdouglas@gmail.com) | Update npm.md | 2017-11-23T00:57:36 | [b5d71ae19600](https://github.com/tldr-pages/tldr/commit/b5d71ae196006ee42cf3c908b545fc86e97c502a)
[Raymond Douglas](mailto:raymondjdouglas@gmail.com) | npm.md: additional module listing use case Added a use case for listing all globally installed modules with a tree depth of 0. | 2017-11-23T00:56:00 | [91c6744c1e1d](https://github.com/tldr-pages/tldr/commit/91c6744c1e1dedc21fb5ca2e1e4da4a82d451e6b)
[Livio Bieri](mailto:livioso@users.noreply.github.com) | Update npm.md | 2016-05-05T16:13:29 | [9f182ee6865d](https://github.com/tldr-pages/tldr/commit/9f182ee6865d3859f25080dae71ccb50757b5175)
[Livio Bieri](mailto:livioso@users.noreply.github.com) | Add npm install --save-dev 🐖 Am I the only one who always forgets if it's --saveDev or --save-dev? My suggestions add --save-dev too. 💩 | 2016-05-04T10:46:42 | [9dc3893c5937](https://github.com/tldr-pages/tldr/commit/9dc3893c5937de5f7cc99651d909523aea0f7756)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | npm: move 'npm install -g' to the top | 2016-01-30T17:15:22 | [f785b8d431ee](https://github.com/tldr-pages/tldr/commit/f785b8d431ee5781d2826843e9ad12601070dcfe)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | npm: removed some examples and added others | 2016-01-30T14:05:05 | [7692a0d13a01](https://github.com/tldr-pages/tldr/commit/7692a0d13a01504160fa6ccb0c502ef6727d949e)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Leandro Ostera](mailto:leandro@ostera.io) | Merge pull request #480 from sonph/patch-1 Add npm -g option | 2015-12-30T21:22:17 | [ca2378a30a4e](https://github.com/tldr-pages/tldr/commit/ca2378a30a4eaba7b7c0e9dfffcb660735ccc46d)
[Son A. Pham](mailto:sp@sonpham.me) | Add npm -g option | 2015-12-30T20:54:13 | [36f1b3ec7267](https://github.com/tldr-pages/tldr/commit/36f1b3ec726711547923a7e9b350e5aadc92cb22)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | minor grammar fix: remove comma | 2015-12-30T15:53:38 | [0c373e9db7b6](https://github.com/tldr-pages/tldr/commit/0c373e9db7b68266c6b05cfdb5baa6e3c646d427)
[Artem Szubowicz](mailto:shybovycha@gmail.com) | Update npm.md Added cleanup | 2015-12-30T14:10:04 | [5222aac447ce](https://github.com/tldr-pages/tldr/commit/5222aac447ce3e07ca8d7e2e9163b59bcb478fcc)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

