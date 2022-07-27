---
author: ['Mateusz Soszyński', 'Reinhart Previano Koentjoro', 'bl-ue']
date: 1651488938
title: "gh issue, TLDR Pages"
description: "gh issue, Manage GitHub issues from the command-line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_issue>.

- Display a specific issue:

```bash
gh issue view issue_number
```

- Display a specific issue in the default web browser:

```bash
gh issue view issue_number --web
```

- Create a new issue in the default web browser:

```bash
gh issue create --web
```

- List the last 10 issues with the `bug` label:

```bash
gh issue list --limit 10 --label "bug"
```

- List closed issues made by a specific user:

```bash
gh issue list --state closed --author username
```

- Display the status of issues relevant to the user, in a specific repository:

```bash
gh issue status --repo owner/repository
```

- Reopen a specific issue:

```bash
gh issue reopen issue_number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | gh*, glab*: standardize documentation (#7957) | 2022-05-02T12:55:38 | [6ed9681dbcd6](https://github.com/tldr-pages/tldr/commit/6ed9681dbcd680e9529c8238221f7fab9cd2c130)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Mateusz Soszyński](mailto:mateusz.soszynski@tuta.io) | gh-issue: add page (#4836) * Add gh issue page * Fix issues from bot * Are you happy now? * Add two more examples * git stash made a [...] | 2020-11-01T03:17:21 | [f51e81fee4b6](https://github.com/tldr-pages/tldr/commit/f51e81fee4b6408f5b1798d23bbdaeafd385221a)

