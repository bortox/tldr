---
author: ['lbonanomi', 'bl-ue', 'Lucas Gabriel Schneider', 'git-em']
date: 1646106761
title: "write"
description: "write, Write a message on the terminal of a specified logged in user (ctrl-C to stop writing messages)."
categories: "common"
---
> Use the `who` command to find out all terminal_ids of all active users active on the system. See also `mesg`.

> More information: <https://manned.org/write>.

- Send a message to a given user on a given terminal id:

```bash
write username terminal_id
```

- Send message to "testuser" on terminal `/dev/tty/5`:

```bash
write testuser tty/5
```

- Send message to "johndoe" on pseudo terminal `/dev/pts/5`:

```bash
write johndoe pts/5
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | set, view, wait, write: add link (#7828) | 2022-03-01T04:52:41 | [80ddce96fed9](https://github.com/tldr-pages/tldr/commit/80ddce96fed97c21dca5e218147f3b15a30d701c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | write: move to common/ | 2019-05-23T18:15:31 | [f30d5ae88691](https://github.com/tldr-pages/tldr/commit/f30d5ae88691bbda5d8c21c25ea0274f4139aa81)

