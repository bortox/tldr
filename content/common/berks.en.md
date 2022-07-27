---
author: ['Marco Bonelli', 'Justin Hao', 'Schneider']
date: 1559564381
title: "berks, TLDR Pages"
description: "berks, Chef cookbook dependency manager."
categories: "common"
---
> More information: <https://docs.chef.io/berkshelf.html>.

- Install cookbook dependencies into a local repo:

```bash
berks install
```

- Update a specific cookbook and its dependencies:

```bash
berks update cookbook
```

- Upload a cookbook to the Chef server:

```bash
berks upload cookbook
```

- View the dependencies of a cookbook:

```bash
berks contingent cookbook
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | berks.md: add homepage | 2019-05-04T15:48:27 | [6bdc5fe2af63](https://github.com/tldr-pages/tldr/commit/6bdc5fe2af63141f1817dcdd085a42a373aede19)
[Justin Hao](mailto:Darkdoughnut@users.noreply.github.com) | berks: add page (#2625) | 2018-11-29T10:42:59 | [615a155f72e0](https://github.com/tldr-pages/tldr/commit/615a155f72e070bda60d2ceb35d442c0e8a12668)

