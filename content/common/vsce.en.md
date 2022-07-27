---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider', 'Owen Voke', 'Jan T. Sott']
date: 1612112718
title: "vsce, TLDR Pages"
description: "vsce, Extension manager for Visual Studio Code."
categories: "common"
---
> More information: <https://github.com/microsoft/vscode-vsce>.

- List all the extensions created by a publisher:

```bash
vsce list publisher
```

- Publish an extension as major, minor or patch version:

```bash
vsce publish major|minor|patch
```

- Unpublish an extension:

```bash
vsce unpublish extension_id
```

- Package the current working directory as a `.vsix` file:

```bash
vsce package
```

- Show the metadata associated with an extension:

```bash
vsce show extension_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Jan T. Sott](mailto:jan@idleberg.com) | vsce: add page (#2229) | 2018-07-31T21:36:59 | [25a028a8b335](https://github.com/tldr-pages/tldr/commit/25a028a8b335103f8cf05e8bb5a20fde33ff4380)

