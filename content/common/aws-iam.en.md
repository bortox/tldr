---
author: ['Elijah Shackelford']
date: 1602540423
title: "aws iam, TLDR Pages"
description: "aws iam, CLI for AWS IAM."
categories: "common"
---
> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/iam/index.html>.

- Show `aws iam` help page (including all available iam commands):

```bash
aws iam help
```

- List users:

```bash
aws iam list-users
```

- List policies:

```bash
aws iam list-policies
```

- List groups:

```bash
aws iam list-groups
```

- Get users in a group:

```bash
aws iam get-group --group-name group_name
```

- Describe an IAM policy:

```bash
aws iam get-policy --policy-arn arn:aws:iam::aws:policy/policy_name
```

- List access keys:

```bash
aws iam list-access-keys
```

- List access keys for a specific user:

```bash
aws iam list-access-keys --user-name user_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Elijah Shackelford](mailto:33649649+eshack94@users.noreply.github.com) | aws iam: add page (#4662) | 2020-10-13T00:07:03 | [00ddf1c66d27](https://github.com/tldr-pages/tldr/commit/00ddf1c66d2763d8fa12f157c14b183a4f3cfb9c)

