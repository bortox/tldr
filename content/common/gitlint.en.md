---
author: ['JaiJoshi123']
date: 1630708874
title: "gitlint"
description: "gitlint, Git commit message linter checks your commit messages for style."
categories: "common"
---
> More information: <https://jorisroovers.com/gitlint/>.

- Check the last commit message:

```bash
gitlint
```

- The range of commits to lint:

```bash
gitlint --commits single_refspec_argument
```

- Path to a directory or python module with extra user-defined rules:

```bash
gitlint --extra-path path/to/directory
```

- Start a specific CI job:

```bash
gitlint --target path/to/target_directory
```

- Path to a file containing a commit-msg:

```bash
gitlint --msg-filename path/to/filename
```

- Read staged commit meta-info from the local repository:

```bash
gitlint --staged
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[JaiJoshi123](mailto:64401010+JaiJoshi123@users.noreply.github.com) | git-bug, git-cola, gitlint: add page (#6444) | 2021-09-04T00:41:14 | [ac40409bbee8](https://github.com/tldr-pages/tldr/commit/ac40409bbee87256b81e82274299e769e7e5e2d5)

