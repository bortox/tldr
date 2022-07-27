---
author: ['Alex Brenon', 'Reinhart Previano Koentjoro', 'bl-ue', 'Axel Navarro']
date: 1651488938
title: "gh repo, TLDR Pages"
description: "gh repo, Work with GitHub repositories on the command-line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_repo>.

- Create a new repository (if the repository name is not set, the default name will be the name of the current directory):

```bash
gh repo create name
```

- Clone a repository:

```bash
gh repo clone owner/repository
```

- Fork and clone a repository:

```bash
gh repo fork owner/repository --clone
```

- View a repository in the default web browser:

```bash
gh repo view repository --web
```

- List repositories owned by a specific user or organization (if the owner is not set, the default owner will be the currently logged in user):

```bash
gh repo list owner
```

- List only non-forks repositories:

```bash
gh repo list owner --non-forks
```

- List repositories with a specific primary coding language:

```bash
gh repo list owner --language language_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | gh*, glab*: standardize documentation (#7957) | 2022-05-02T12:55:38 | [6ed9681dbcd6](https://github.com/tldr-pages/tldr/commit/6ed9681dbcd680e9529c8238221f7fab9cd2c130)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-repo: add examples for list subcommand (#5358) | 2021-03-10T15:27:12 | [55d538857837](https://github.com/tldr-pages/tldr/commit/55d5388578374751fe1534edc54ba2ee8f44aa74)
[Alex Brenon](mailto:alex@alexroseb.com) | gh-repo: add page (#4897) | 2020-11-04T19:37:36 | [5511382eede1](https://github.com/tldr-pages/tldr/commit/5511382eede17ef871dfed786f615c8ee7b0dbf8)

