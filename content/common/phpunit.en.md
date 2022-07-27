---
author: ['Mario Döring', 'Ruben Vereecken', 'Wolfgang Lutz', 'pxgamer']
date: 1559328460
title: "phpunit, TLDR Pages"
description: "phpunit, PHPUnit command-line test runner."
categories: "common"
---
> More information: <https://phpunit.de>.

- Run tests in the current directory. Note: Expects you to have a 'phpunit.xml':

```bash
phpunit
```

- Run tests in a specific file:

```bash
phpunit path/to/TestFile.php
```

- Run tests annotated with the given group:

```bash
phpunit --group name
```

- Run tests and generate a coverage report in HTML:

```bash
phpunit --coverage-html directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | phpunit: add link to homepage | 2019-05-31T20:47:40 | [ef21ff7798db](https://github.com/tldr-pages/tldr/commit/ef21ff7798db2f9bb03dc101dfcc7f52a0eea46a)
[Wolfgang Lutz](mailto:WLBORg@gmx.de) | fix typos using misspell (#1374) | 2017-05-12T11:29:18 | [550ede5cfb90](https://github.com/tldr-pages/tldr/commit/550ede5cfb90cb772d1ecf27241b22e5086b024b)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Mario Döring](mailto:deluna.yy@gmail.com) | Added common/phpunit.md page and examples. | 2015-12-29T16:50:01 | [735588e0a111](https://github.com/tldr-pages/tldr/commit/735588e0a111e4097f2912dca407410005cbee99)

