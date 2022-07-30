---
author: ['Axel Navarro', 'bl-ue', 'Mateusz Soszyński', 'marchersimon']
date: 1621541621
title: "gh auth"
description: "gh auth, Authenticate with a GitHub host from the command-line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_auth>.

- Log in with interactive prompt:

```bash
gh auth login
```

- Log in with a token from standard input (created in https://github.com/settings/tokens):

```bash
echo your_token | gh auth login --with-token
```

- Check if you are logged in:

```bash
gh auth status
```

- Log out:

```bash
gh auth logout
```

- Log in with a specific GitHub Enterprise Server:

```bash
gh auth login --hostname github.example.com
```

- Refresh the session to ensure authentication credentials have the correct minimum scopes (removes additional scopes requested previously):

```bash
gh auth refresh
```

- Expand the permission scopes:

```bash
gh auth refresh --scopes write:org,read:public_key
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-auth: add refresh examples (#5306) | 2021-02-24T14:11:22 | [d9a692b950d9](https://github.com/tldr-pages/tldr/commit/d9a692b950d97fcee277ca28b627c142a8d46956)
[Mateusz Soszyński](mailto:mateusz.soszynski@tuta.io) | gh-auth: add page (#4839) | 2020-10-26T11:14:22 | [d2a24aaf37d3](https://github.com/tldr-pages/tldr/commit/d2a24aaf37d3459fd90c30c0444b8d175570ee64)

