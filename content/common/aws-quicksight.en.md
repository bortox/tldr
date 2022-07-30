---
author: ['ahonarmand', 'marchersimon']
date: 1618154950
title: "aws quicksight"
description: "aws quicksight, CLI for AWS QuickSight."
categories: "common"
---
> Access QuickSight entities.

> More information: <https://docs.aws.amazon.com/cli/latest/reference/quicksight/>.

- List datasets:

```bash
aws quicksight list-data-sets --aws-account-id aws_account_id
```

- List users:

```bash
aws quicksight list-users --aws-account-id aws_account_id --namespace default
```

- List groups:

```bash
aws quicksight list-groups --aws-account-id aws_account_id --namespace default
```

- List dashboards:

```bash
aws quicksight list-dashboards --aws-account-id aws_account_id
```

- Display detailed information about a dataset:

```bash
aws quicksight describe-data-set --aws-account-id aws_account_id --data-set-id data_set_id
```

- Display who has access to the dataset and what kind of actions they can perform on the dataset:

```bash
aws quicksight describe-data-set-permissions --aws-account-id aws_account_id --data-set-id data_set_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | remove index.html from more information links where posible | 2021-04-11T17:29:10 | [1e2f4f202a9e](https://github.com/tldr-pages/tldr/commit/1e2f4f202a9e7827b670bd2db5d1cb776316df06)
[ahonarmand](mailto:72367678+ahonarmand@users.noreply.github.com) | aws quicksight: add page (#4738) | 2020-10-19T19:20:06 | [8400c98f2af1](https://github.com/tldr-pages/tldr/commit/8400c98f2af10249b0dc36c66f659e37e57017f3)

