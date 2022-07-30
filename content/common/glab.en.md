---
author: ['marchersimon', 'bl-ue', 'Bradley Garrod', 'Reinhart Previano Koentjoro']
date: 1651488938
title: "glab"
description: "glab, Work seamlessly with GitLab from the command-line."
categories: "common"
---
> Some subcommands such as `glab config` have their own usage documentation.

> More information: <https://github.com/profclems/glab>.

- Clone a GitLab repository locally:

```bash
glab repo clone owner/repository
```

- Create a new issue:

```bash
glab issue create
```

- View and filter the open issues of the current repository:

```bash
glab issue list
```

- View an issue in the default browser:

```bash
glab issue view --web issue_number
```

- Create a merge request:

```bash
glab mr create
```

- View a pull request in the default web browser:

```bash
glab mr view --web pr_number
```

- Check out a specific pull request locally:

```bash
glab mr checkout pr_number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | gh*, glab*: standardize documentation (#7957) | 2022-05-02T12:55:38 | [6ed9681dbcd6](https://github.com/tldr-pages/tldr/commit/6ed9681dbcd680e9529c8238221f7fab9cd2c130)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Bradley Garrod](mailto:32489229+BreD1810@users.noreply.github.com) | glab: add page (#4254) | 2020-08-12T01:34:55 | [c133f38b6989](https://github.com/tldr-pages/tldr/commit/c133f38b6989ee1939919f299b0dbc1cbc80e1ce)

