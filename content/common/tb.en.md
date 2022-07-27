---
author: ['Marco Bonelli', 'Guido Lena Cota', 'Yannis Huber', 'pxgamer']
date: 1604238005
title: "tb, TLDR Pages"
description: "tb, CLI for managing tasks and notes across multiple boards."
categories: "common"
---
> More information: <https://github.com/klaussinani/taskbook>.

- Add a new task to a board:

```bash
tb --task task_description @board_name
```

- Add a new note to a board:

```bash
tb --note note_description @board_name
```

- Edit item's priority:

```bash
tb --priority @item_id priority
```

- Check/uncheck item:

```bash
tb --check item_id
```

- Archive all checked items:

```bash
tb --clear
```

- Move item to a board:

```bash
tb --move @item_id board_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | tb: add link to homepage | 2019-05-14T19:58:59 | [d1f8b5a3c62f](https://github.com/tldr-pages/tldr/commit/d1f8b5a3c62ff5c92248d6eff17b754b05b88fb1)
[Yannis Huber](mailto:32066446+yannishuber@users.noreply.github.com) | tb: add page (#2630) | 2018-12-02T15:52:05 | [c6850f8e3754](https://github.com/tldr-pages/tldr/commit/c6850f8e375448cd56c9a10a40e0f8667d351b40)

