---
author: ['Schneider', 'Marco Bonelli', 'Maxime Veber', 'Guido Lena Cota', 'Starbeamrainbowlabs']
date: 1592564072
title: "composer, TLDR Pages"
description: "composer, A package-based dependency manager for PHP projects."
categories: "common"
---
> More information: <https://getcomposer.org/>.

- Interactively create a `composer.json` file:

```bash
composer init
```

- Add a package as a dependency for this project, adding it to `composer.json`:

```bash
composer require user/package_name
```

- Install all the dependencies in this project's `composer.json` and create `composer.lock`:

```bash
composer install
```

- Uninstall a package from this project, removing it as a dependency from `composer.json`:

```bash
composer remove user/package_name
```

- Update all the dependencies in this project's `composer.json` and note versions in `composer.lock` file:

```bash
composer update
```

- Update composer lock only after updating `composer.json` manually:

```bash
composer update --lock
```

- Learn more about why a dependency can't be installed:

```bash
composer why-not user/package_name
```

- Update composer to its latest version:

```bash
composer self-update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Maxime Veber](mailto:nek.dev@gmail.com) | composer: more information (#4111) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-06-19T12:54:32 | [fb0fed50fdec](https://github.com/tldr-pages/tldr/commit/fb0fed50fdecee86083a11e4d79b5e657f177439)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | composer.md: add homepage | 2019-05-04T15:48:27 | [e0342ee8cd50](https://github.com/tldr-pages/tldr/commit/e0342ee8cd50d1bf2ac3a065c521c02363042e53)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mass change: apply snake case to tokens (#2518) | 2018-10-29T12:14:25 | [18370557b25e](https://github.com/tldr-pages/tldr/commit/18370557b25e5340d9ee5cfeee346ce8fcb4ef95)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | composer: add page (#1329) | 2017-04-20T13:27:57 | [3f53e3282f61](https://github.com/tldr-pages/tldr/commit/3f53e3282f619bc81d7a0ab25c92bb6b4bfcc4be)

