---
author: ['lucas schneider', 'Lucas Gabriel Schneider', 'Luke (Burbidge) Alvarez']
date: 1610111394
title: "Chezmoi"
description: "Chezmoi, A multi-machine dotfile manager, written in Go."
categories: "common"
---
> More information: <https://chezmoi.io>.

- Initialize chezmoi on your machine:

```bash
chezmoi init
```

- Tell chezmoi to manage a dotfile:

```bash
chezmoi add path/to/file
```

- Edit the source state of a tracked dotfile:

```bash
chezmoi edit path/to/file
```

- See changes chezmoi would make:

```bash
chezmoi diff
```

- Apply the changes:

```bash
chezmoi -v apply
```

- Set chezmoi up on another machine by downloading existing dotfiles from a Git repository:

```bash
chezmoi init https://example.com/path/to/repository.git
```

- Fetch the latest changes from a remote repository:

```bash
chezmoi update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | Update pages/common/chezmoi.md Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-01-08T14:09:54 | [fddaac3d0ab3](https://github.com/tldr-pages/tldr/commit/fddaac3d0ab3d3fae5f04fe9a2625fcfcbaf4381)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Luke (Burbidge) Alvarez](mailto:lburbidg@ucsd.edu) | chezmoi: add page (#4314) | 2020-09-27T05:46:58 | [42780dc7aa91](https://github.com/tldr-pages/tldr/commit/42780dc7aa91874a7fb63ceb3f78bc61a0af6406)

