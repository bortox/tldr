---
author: ['Reinhart Previano Koentjoro', 'Abel', 'bl-ue', 'Axel Navarro']
date: 1651488938
title: "gh pr, TLDR Pages"
description: "gh pr, Manage GitHub pull requests from the command-line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_pr>.

- Create a pull request:

```bash
gh pr create
```

- Check out a specific pull request locally:

```bash
gh pr checkout pr_number
```

- View the changes made in the pull request for the current branch:

```bash
gh pr diff
```

- Approve the pull request for the current branch:

```bash
gh pr review --approve
```

- Merge the pull request associated with the current branch interactively:

```bash
gh pr merge
```

- Edit a pull request interactively:

```bash
gh pr edit
```

- Edit the base branch of a pull request:

```bash
gh pr edit --base branch_name
```

- Check the status of the current repository's pull requests:

```bash
gh pr status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | gh*, glab*: standardize documentation (#7957) | 2022-05-02T12:55:38 | [6ed9681dbcd6](https://github.com/tldr-pages/tldr/commit/6ed9681dbcd680e9529c8238221f7fab9cd2c130)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-pr-merge: add page (#5731) | 2021-04-15T19:04:49 | [fa468e6eb568](https://github.com/tldr-pages/tldr/commit/fa468e6eb568b02ed41b48049488ee277389b5af)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-pr: add examples for edit subcommand (#5359) | 2021-03-08T21:27:00 | [cc5b7163407e](https://github.com/tldr-pages/tldr/commit/cc5b7163407e836b86aa0dde9e52c625d8abb6f9)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-pr: fix page title (#5126) | 2021-01-11T17:23:31 | [e3fb724b415c](https://github.com/tldr-pages/tldr/commit/e3fb724b415c0bead0cfecdb385db384f32c8acc)
[Abel](mailto:abel.tay@gmail.com) | gh-pr: add page (#4717) | 2020-10-19T19:29:43 | [0be5e3adaf82](https://github.com/tldr-pages/tldr/commit/0be5e3adaf8292e5aef3f3ee7c926c38686821cd)

