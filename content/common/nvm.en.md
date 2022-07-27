---
author: ['Waldir Pimenta', 'Reinhart Previano Koentjoro', 'Marco Bonelli', 'Ruben Vereecken', 'Igor Shubovych']
date: 1639319694
title: "nvm, TLDR Pages"
description: "nvm, Install, uninstall or switch between Node.js versions."
categories: "common"
---
> Supports version numbers like "12.8" or "v16.13.1", and labels like "stable", "system", etc.

> More information: <https://github.com/creationix/nvm>.

- Install a specific version of Node.js:

```bash
nvm install node_version
```

- Use a specific version of Node.js in the current shell:

```bash
nvm use node_version
```

- Set the default Node.js version:

```bash
nvm alias default node_version
```

- List all available Node.js versions and highlight the default one:

```bash
nvm list
```

- Uninstall a given Node.js version:

```bash
nvm uninstall node_version
```

- Launch the REPL of a specific version of Node.js:

```bash
nvm run node_version --version
```

- Execute a script in a specific version of Node.js:

```bash
nvm exec node_version node app.js
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | nvm: update versions in command description (#7518) | 2021-12-12T15:34:54 | [a0bb234f064f](https://github.com/tldr-pages/tldr/commit/a0bb234f064feaeb8e225fb28cbb319c481e3dde)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | nvm: update and expand page - Add uninstall command - Improve some command descriptions - Reword main description - Standardize [...] | 2019-01-11T05:06:49 | [52bd8f25ba05](https://github.com/tldr-pages/tldr/commit/52bd8f25ba0579229e986b7e5b1ddc0d53306e7c)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | nvm: add page | 2015-12-26T10:40:13 | [4cbd8a356c14](https://github.com/tldr-pages/tldr/commit/4cbd8a356c14e3e7923fc17266e31afea03b8f93)

