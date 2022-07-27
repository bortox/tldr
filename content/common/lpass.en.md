---
author: ['Halvor Haukvik', 'pxgamer', 'Lucas Gabriel Schneider', 'bl-ue', 'marchersimon']
date: 1621541621
title: "lpass, TLDR Pages"
description: "lpass, Command-line interface for the LastPass password manager."
categories: "common"
---
> More information: <https://github.com/lastpass/lastpass-cli>.

- Log in to your LastPass account, by entering your master password when prompted:

```bash
lpass login username
```

- Show login status:

```bash
lpass status
```

- List all sites grouped by category:

```bash
lpass ls
```

- Generate a new password for gmail.com with the identifier `myinbox` and add to LastPass:

```bash
lpass generate --username username --url gmail.com myinbox password_length
```

- Show password for a specified entry:

```bash
lpass show myinbox --password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | lpass: add link to homepage | 2019-06-06T04:42:48 | [4c5d4fbe533a](https://github.com/tldr-pages/tldr/commit/4c5d4fbe533a84af2f330680b13f98af2630e40f)
[Halvor Haukvik](mailto:hdhauk@users.noreply.github.com) | lpass: add page (#1815) | 2017-12-20T04:16:39 | [e2f15e747001](https://github.com/tldr-pages/tldr/commit/e2f15e7470014dd811be52c952d58af6d95b7e36)

