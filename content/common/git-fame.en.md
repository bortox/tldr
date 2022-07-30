---
author: ['bl-ue']
date: 1621896321
title: "git fame"
description: "git fame, Pretty-print Git repository contributions."
categories: "common"
---
> More information: <https://github.com/casperdcl/git-fame>.

- Calculate contributions for the current Git repository:

```bash
git fame
```

- Exclude files/directories that match the specified regular expression:

```bash
git fame --excl "regular_expression"
```

- Calculate contributions made after the specified date:

```bash
git fame --since "3 weeks ago|2021-05-13"
```

- Display contributions in the specified format:

```bash
git fame --format pipe|yaml|json|csv|tsv
```

- Display contributions per file extension:

```bash
git fame --bytype
```

- Ignore whitespace changes:

```bash
git fame --ignore-whitespace
```

- Detect inter-file line moves and copies:

```bash
git fame -C
```

- Detect intra-file line moves and copies:

```bash
git fame -M
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-fame: add page (#6012) | 2021-05-25T00:45:21 | [2ffe2276df45](https://github.com/tldr-pages/tldr/commit/2ffe2276df454824d35370331a8f90308ce63e4f)

