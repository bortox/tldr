---
author: ['bl-ue', 'Lucas Gabriel Schneider', 'Alex Brenon']
date: 1621541621
title: "gh gist"
description: "gh gist, Work with GitHub Gists on the command-line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_gist>.

- Create a new Gist from a space-separated list of files:

```bash
gh gist create path/to/files
```

- Create a new Gist with a description:

```bash
gh gist create filename --desc "description"
```

- Edit a Gist:

```bash
gh gist edit id_or_url
```

- List Gists owned by the currently logged in user:

```bash
gh gist list --limit int
```

- View a Gist in the default browser without rendering Markdown:

```bash
gh gist view id_or_url --web --raw
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | change markdown to Markdown (#5049) | 2020-12-29T12:45:05 | [8b80cf08b84a](https://github.com/tldr-pages/tldr/commit/8b80cf08b84aec781c99c2a42c7acf95bab446cf)
[Alex Brenon](mailto:alex@alexroseb.com) | gh-gist: add page (#4898) | 2020-11-06T12:02:47 | [28a29bf304ee](https://github.com/tldr-pages/tldr/commit/28a29bf304eec5904f1131c2f1fb11212c2d4f1e)

