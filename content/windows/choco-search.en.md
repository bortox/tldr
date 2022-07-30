---
author: ['Owen Voke', 'pxgamer', 'Marco Bonelli']
date: 1559564381
title: "choco search"
description: "choco search, Search for a local or remote package with Chocolatey."
categories: "windows"
---
> More information: <https://chocolatey.org/docs/commands-search>.

- Search for a package:

```bash
choco search query
```

- Search for a package locally:

```bash
choco search query --local-only
```

- Only include exact matches in the results:

```bash
choco search query --exact
```

- Confirm all prompts automatically:

```bash
choco search query --yes
```

- Specify a custom source to search for packages in:

```bash
choco search query --source source_url|alias
```

- Provide a username and password for authentication:

```bash
choco search query --user username --password password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | choco-search: add link to homepage | 2019-03-20T06:53:44 | [500640acd11f](https://github.com/tldr-pages/tldr/commit/500640acd11f076d6b2d69742e2f0e8b3e26cb24)
[Owen Voke](mailto:owzie123@gmail.com) | choco-search: add page (#2031) | 2018-03-15T17:59:30 | [dcefcf123070](https://github.com/tldr-pages/tldr/commit/dcefcf12307006b501d985c84eaa10dcd080a1c6)

