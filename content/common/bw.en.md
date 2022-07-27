---
author: ['Marco Bonelli', 'Nithya', 'Schneider']
date: 1559564381
title: "bw, TLDR Pages"
description: "bw, A CLI to access and manage a Bitwarden vault."
categories: "common"
---
> More information: <https://help.bitwarden.com/article/cli/>.

- Log in to a Bitwarden user account:

```bash
bw login
```

- Log out of a Bitwarden user account:

```bash
bw logout
```

- Search and display items from Bitwarden vault:

```bash
bw list items --search github
```

- Display a particular item from Bitwarden vault:

```bash
bw get item github
```

- Create a folder in Bitwarden vault:

```bash
echo -n '{"name":"My Folder1"}' | base64 | bw create folder
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | bw.md: add homepage | 2019-04-12T14:41:22 | [96090e52b72f](https://github.com/tldr-pages/tldr/commit/96090e52b72f8e093c9c9da7bccbb171e1a20bde)
[Nithya](mailto:nithyanatarajn@gmail.com) | bw: add page (#2537) | 2018-11-04T12:29:37 | [0d17eabb7fee](https://github.com/tldr-pages/tldr/commit/0d17eabb7fee28e4121ddf42af45f0684777626f)

