---
author: ['Reinhart Previano Koentjoro']
date: 1651488938
title: "glab issue"
description: "glab issue, Manage GitLab issues from the command-line."
categories: "common"
---
> More information: <https://glab.readthedocs.io/en/latest/issue>.

- Display a specific issue:

```bash
glab issue view issue_number
```

- Display a specific issue in the default web browser:

```bash
glab issue view issue_number --web
```

- Create a new issue in the default web browser:

```bash
glab issue create --web
```

- List the last 10 issues with the `bug` label:

```bash
glab issue list --per-page 10 --label "bug"
```

- List closed issues made by a specific user:

```bash
glab issue list --closed --author username
```

- Reopen a specific issue:

```bash
glab issue reopen issue_number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | gh*, glab*: standardize documentation (#7957) | 2022-05-02T12:55:38 | [6ed9681dbcd6](https://github.com/tldr-pages/tldr/commit/6ed9681dbcd680e9529c8238221f7fab9cd2c130)
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | glab-issue: add page (#7615) | 2022-01-18T14:59:48 | [0c8ed2af5c51](https://github.com/tldr-pages/tldr/commit/0c8ed2af5c515d244c98e04dacfdb6c435f99837)

