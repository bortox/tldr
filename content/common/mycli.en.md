---
author: ['bl-ue', 'Ljqiii']
date: 1621541621
title: "mycli"
description: "mycli, A command-line client for MySQL that can do auto-completion and syntax highlighting."
categories: "common"
---
> More information: <https://mycli.net>.

- Connect to a local database on port 3306, using the current user's username:

```bash
mycli database_name
```

- Connect to a database (user will be prompted for a password):

```bash
mycli -u username database_name
```

- Connect to a database on another host:

```bash
mycli -h database_host -P port -u username database_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ljqiii](mailto:ljq917181927@gmail.com) | mycli: add page (#3116) | 2019-06-22T17:37:46 | [05daa0891de1](https://github.com/tldr-pages/tldr/commit/05daa0891de17844f1bb25d0ac181a061a5bf289)

