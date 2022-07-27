---
author: ['Reinhart Previano Koentjoro']
date: 1651488938
title: "glab mr, TLDR Pages"
description: "glab mr, Manage GitLab merge requests from the command-line."
categories: "common"
---
> Some subcommands such as `glab mr create` have their own usage documentation.

> More information: <https://glab.readthedocs.io/en/latest/mr>.

- Create a merge request:

```bash
glab mr create
```

- Check out a specific merge request locally:

```bash
glab mr checkout mr_number
```

- View the changes made in the merge request:

```bash
glab mr diff
```

- Approve the merge request for the current branch:

```bash
glab mr approve
```

- Merge the merge request associated with the current branch interactively:

```bash
glab mr merge
```

- Edit a merge request interactively:

```bash
glab mr update
```

- Edit the target branch of a merge request:

```bash
glab mr update --target-branch branch_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | gh*, glab*: standardize documentation (#7957) | 2022-05-02T12:55:38 | [6ed9681dbcd6](https://github.com/tldr-pages/tldr/commit/6ed9681dbcd680e9529c8238221f7fab9cd2c130)
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | glab-mr*: add pages (#7635) | 2022-01-11T16:29:47 | [285609b2399b](https://github.com/tldr-pages/tldr/commit/285609b2399b62b066295a89b4844c83d376af6d)

