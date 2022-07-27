---
author: ['Philipp Weißmann', 'Owen Voke', 'Marco Bonelli', 'lucas schneider', 'Lucas Gabriel Schneider']
date: 1612112718
title: "vcsh, TLDR Pages"
description: "vcsh, Version Control System for the home directory using Git repositories."
categories: "common"
---
> More information: <https://github.com/RichiH/vcsh>.

- Initialize an (empty) repository:

```bash
vcsh init repository_name
```

- Clone a repository into a custom directory name:

```bash
vcsh clone git_url repository_name
```

- List all managed repositories:

```bash
vcsh list
```

- Execute a Git command on a managed repository:

```bash
vcsh repository_name git_command
```

- Push/pull all managed repositories to/from remotes:

```bash
vcsh push|pull
```

- Write a custom `.gitignore` file for a managed repository:

```bash
vcsh write-gitignore repository_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Philipp Weißmann](mailto:github@philipp-weissmann.de) | vcsh: add page (#2338) | 2018-09-24T18:19:29 | [43f95b28942b](https://github.com/tldr-pages/tldr/commit/43f95b28942bcf4cdc288bbf2e73acf23ceb97b1)

