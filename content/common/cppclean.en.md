---
author: ['pxgamer', 'Lucas Gabriel Schneider', 'Thomas BARUSSEAU', 'Marco Bonelli']
date: 1612112718
title: "cppclean"
description: "cppclean, Find unused code in C++ projects."
categories: "common"
---
> More information: <https://github.com/myint/cppclean>.

- Run in a project's directory:

```bash
cppclean path/to/project
```

- Run on a project where the headers are in the `inc1/` and `inc2/` directories:

```bash
cppclean path/to/project --include-path=inc1 --include-path=inc2
```

- Run on a specific file `main.cpp`:

```bash
cppclean main.cpp
```

- Run on the current directory, excluding the "build" directory:

```bash
cppclean . --exclude=build
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | cppclean: add link to homepage | 2019-06-09T18:53:49 | [37408feb00dc](https://github.com/tldr-pages/tldr/commit/37408feb00dcf7f17355da89a889abaeedf2d693)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Thomas BARUSSEAU](mailto:Thomas.BARUSSEAU@ingenico.com) | cppclean: updated page | 2017-12-05T09:35:52 | [fc26f34a0b43](https://github.com/tldr-pages/tldr/commit/fc26f34a0b43fe3922ebcf2667844dd08c2c871f)
[Thomas BARUSSEAU](mailto:Thomas.BARUSSEAU@ingenico.com) | cppclean: add page | 2017-12-04T16:05:17 | [d2040640dcec](https://github.com/tldr-pages/tldr/commit/d2040640dcecf2653d5308a20fe698dc11d83f72)

