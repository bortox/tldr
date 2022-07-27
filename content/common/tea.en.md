---
author: ['bl-ue', 'Owen Voke']
date: 1621541621
title: "tea, TLDR Pages"
description: "tea, A command-line tool to interact with Gitea servers."
categories: "common"
---
> More information: <https://gitea.com/gitea/tea>.

- Log into a Gitea server:

```bash
tea login add --name "name" --url "url" --token "token"
```

- Display all repositories:

```bash
tea repos ls
```

- Display a list of issues:

```bash
tea issues ls
```

- Display a list of issues for a specific repository:

```bash
tea issues ls --repo "repository"
```

- Create a new issue:

```bash
tea issues create --title "title" --body "body"
```

- Display a list of open pull requests:

```bash
tea pulls ls
```

- Open the current repository in a browser:

```bash
tea open
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Owen Voke](mailto:development@voke.dev) | tea: add page (#4023) | 2020-05-08T14:02:16 | [503ba15ee7d2](https://github.com/tldr-pages/tldr/commit/503ba15ee7d2d77e76feb44174cd48cf6375a51d)

