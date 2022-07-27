---
author: ['Marco Bonelli', 'Ruben Vereecken', 'pxgamer', 'Kyle Kamperschroer', 'marchersimon']
date: 1620637392
title: "mocha, TLDR Pages"
description: "mocha, Execute Mocha JavaScript test runner."
categories: "common"
---
> More information: <https://mochajs.org>.

- Run tests with default configuration or as configured in `mocha.opts`:

```bash
mocha
```

- Run tests contained at a specific location:

```bash
mocha directory/with/tests
```

- Run tests that match a specific grep pattern:

```bash
mocha --grep regular_expression
```

- Run tests on changes to JavaScript files in the current directory and once initially:

```bash
mocha --watch
```

- Run tests with a specific reporter:

```bash
mocha --reporter reporter
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[pxgamer](mailto:owzie123@gmail.com) | mocha: add link to homepage | 2019-06-04T21:29:40 | [f9a60da0d73b](https://github.com/tldr-pages/tldr/commit/f9a60da0d73b0e44fadf4876773727ee1499b25a)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Kyle Kamperschroer](mailto:kyle.kamperschroer@attackpattern.com) | Add mocha.md | 2016-01-06T18:42:22 | [186d3f2e25f2](https://github.com/tldr-pages/tldr/commit/186d3f2e25f25c0a30e51e84f11cde10fa79d120)

