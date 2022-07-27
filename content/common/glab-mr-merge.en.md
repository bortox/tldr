---
author: ['Reinhart Previano Koentjoro']
date: 1641914987
title: "glab mr merge, TLDR Pages"
description: "glab mr merge, Merge GitLab merge requests."
categories: "common"
---
> More information: <https://glab.readthedocs.io/en/latest/mr/merge.html>.

- Merge the merge request associated with the current branch interactively:

```bash
glab mr merge
```

- Merge the specified merge request, interactively:

```bash
glab mr merge mr_number
```

- Merge the merge request, removing the branch on both the local and the remote:

```bash
glab mr merge --remove-source-branch
```

- Squash the current merge request into one commit with the message body and merge:

```bash
glab mr merge --squash --message="commit_message_body"
```

- Display help:

```bash
glab mr merge --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | glab-mr*: add pages (#7635) | 2022-01-11T16:29:47 | [285609b2399b](https://github.com/tldr-pages/tldr/commit/285609b2399b62b066295a89b4844c83d376af6d)

