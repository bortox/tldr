---
author: ['Marco Bonelli', 'Thomas Wünsche', 'pxgamer', 'thezeroalpha']
date: 1609783301
title: "rbenv, TLDR Pages"
description: "rbenv, A tool to easily install Ruby versions and manage application environments."
categories: "common"
---
> More information: <https://github.com/rbenv/rbenv>.

- Install a Ruby version:

```bash
rbenv install version
```

- Display a list of the latest stable versions for each Ruby:

```bash
rbenv install --list
```

- Display a list of installed Ruby versions:

```bash
rbenv versions
```

- Use a specific Ruby version across the whole system:

```bash
rbenv global version
```

- Use a specific Ruby version for an application/project directory:

```bash
rbenv local version
```

- Display the currently selected Ruby version:

```bash
rbenv version
```

- Uninstall a Ruby version:

```bash
rbenv uninstall version
```

- Display all Ruby versions that contain the specified executable:

```bash
rbenv whence executable
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Thomas Wünsche](mailto:42999314+thomaswuensche@users.noreply.github.com) | rbenv: add example and improve page (#5084) | 2021-01-04T19:01:41 | [325a88c9241f](https://github.com/tldr-pages/tldr/commit/325a88c9241f770756248ddf11a9fc73062cc23d)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | rbenv: add link to homepage | 2019-05-29T14:41:10 | [9d5a963d9738](https://github.com/tldr-pages/tldr/commit/9d5a963d9738e42373c2f120ba1fc54a233d2c04)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[thezeroalpha](mailto:8124851+thezeroalpha@users.noreply.github.com) | rbenv: add page (#2133) | 2018-06-14T19:08:50 | [c0f023b573c8](https://github.com/tldr-pages/tldr/commit/c0f023b573c88c46a389058394699490cb2fdf9f)

