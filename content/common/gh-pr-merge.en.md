---
author: ['Axel Navarro']
date: 1643777500
title: "gh pr merge, TLDR Pages"
description: "gh pr merge, Merge GitHub pull requests."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_pr_merge>.

- Merge the pull request associated with the current branch interactively:

```bash
gh pr merge
```

- Merge the specified pull request, interactively:

```bash
gh pr merge pr_number
```

- Merge the pull request, removing the branch on both the local and the remote:

```bash
gh pr merge --delete-branch
```

- Merge the current pull request with the specified merge strategy:

```bash
gh pr merge --merge|squash|rebase
```

- Merge the current pull request with the specified merge strategy and commit message:

```bash
gh pr merge --merge|squash|rebase --subject commit_message
```

- Squash the current pull request into one commit with the message body and merge:

```bash
gh pr merge --squash --body="commit_message_body"
```

- Display help:

```bash
gh pr merge --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-pr-merge: add --subject example (#7732) | 2022-02-02T05:51:40 | [8b9b6e98b56e](https://github.com/tldr-pages/tldr/commit/8b9b6e98b56eace63cfaa5def2e7aeccfc396ed6)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-pr-merge: add --help example (#6040) | 2021-05-24T18:28:06 | [7f934c75947e](https://github.com/tldr-pages/tldr/commit/7f934c75947ef704ada23acb5e05cb0d7dff3603)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-pr-merge: add page (#5731) | 2021-04-15T19:04:49 | [fa468e6eb568](https://github.com/tldr-pages/tldr/commit/fa468e6eb568b02ed41b48049488ee277389b5af)

