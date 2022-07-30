---
author: ['vkolmakov', 'Waldir Pimenta', 'Starbeamrainbowlabs', 'Marco Bonelli']
date: 1559564381
title: "yarn"
description: "yarn, JavaScript and Node.js package manager alternative."
categories: "common"
---
> More information: <https://yarnpkg.com>.

- Install a module globally:

```bash
yarn global add module_name
```

- Install all dependencies referenced in the `package.json` file (the `install` is optional):

```bash
yarn install
```

- Install a module and save it as a dependency to the `package.json` file (add `--dev` to save as a dev dependency):

```bash
yarn add module_name@version
```

- Uninstall a module and remove it from the `package.json` file:

```bash
yarn remove module_name
```

- Interactively create a `package.json` file:

```bash
yarn init
```

- Identify whether a module is a dependency and list other modules that depend upon it:

```bash
yarn why module_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | yarn: make the install example more explicit Also format code in other examples with backticks | 2018-12-03T12:48:30 | [9ebd2486ef04](https://github.com/tldr-pages/tldr/commit/9ebd2486ef04b6d7882cc6bdc8eeb2e3fb4a1f9d)
[vkolmakov](mailto:vkolmakov@hotmail.com) | Rephrase why command description and minor fixes | 2016-10-17T05:10:01 | [7b3cf933c0a6](https://github.com/tldr-pages/tldr/commit/7b3cf933c0a62363e6e0ec7d6c2a09c917bc2391)
[vkolmakov](mailto:vkolmakov@hotmail.com) | Merge add and add-dev and remove ls | 2016-10-17T01:46:48 | [165e1ded0b52](https://github.com/tldr-pages/tldr/commit/165e1ded0b52407da328c45b140b24dd34681607)
[vkolmakov](mailto:vkolmakov@hotmail.com) | yarn: add page | 2016-10-17T00:24:40 | [81a9c4fedd9b](https://github.com/tldr-pages/tldr/commit/81a9c4fedd9b49d97ac512aa7b0fbb0fddf25c93)

