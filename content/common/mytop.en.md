---
author: ['Marco Bonelli', 'Aşkın Özgür', 'marchersimon']
date: 1625253777
title: "mytop"
description: "mytop, Display MySQL server performance info like `top`."
categories: "common"
---
> More information: <http://jeremy.zawodny.com/mysql/mytop/mytop.html>.

- Start mytop:

```bash
mytop
```

- Connect with a specified username and password:

```bash
mytop -u user -p password
```

- Connect with a specified username (the user will be prompted for a password):

```bash
mytop -u user --prompt
```

- Do not show any idle (sleeping) threads:

```bash
mytop -u user -p password --noidle
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Aşkın Özgür](mailto:askin@askin.ws) | mytop: add page (#2741) | 2019-01-31T19:12:12 | [bcd42b505217](https://github.com/tldr-pages/tldr/commit/bcd42b505217302a9056e63168bd9c6555ebeb02)

