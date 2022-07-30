---
author: ['Joshua Casey', 'Lucas Gabriel Schneider', 'Thamaraiselvam', 'Francesco Franchina']
date: 1635196708
title: "direnv"
description: "direnv, Shell extension to load and unload environment variables depending on the current directory."
categories: "common"
---
> More information: <https://github.com/direnv/direnv>.

- Grant direnv permission to load the `.envrc` present in the current directory:

```bash
direnv allow .
```

- Revoke the authorization to load the `.envrc` present in the current directory:

```bash
direnv deny .
```

- Edit the `.envrc` file in the default text editor and reload the environment on exit:

```bash
direnv edit .
```

- Trigger a reload of the environment:

```bash
direnv reload
```

- Print some debug status information:

```bash
direnv status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Francesco Franchina](mailto:cescus92@gmail.com) | direnv: clarification in the examples and Italian translation (#7001) | 2021-10-25T23:18:28 | [61b7666a76b1](https://github.com/tldr-pages/tldr/commit/61b7666a76b1d848c53b98af1194ccbe0c6d1789)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Joshua Casey](mailto:joshuatcasey@gmail.com) | direnv: fix typo in edit example (#5041) | 2020-12-27T02:19:32 | [981b2bea366b](https://github.com/tldr-pages/tldr/commit/981b2bea366bb216a8c9c409d9fc42c8dc19127e)
[Thamaraiselvam](mailto:thamaraiselvam@live.com) | direnv: add page (#4392) | 2020-10-24T14:29:25 | [9da373b089cd](https://github.com/tldr-pages/tldr/commit/9da373b089cd6a918295c2f66419884364eb0b05)

