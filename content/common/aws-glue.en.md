---
author: ['ahonarmand', 'marchersimon']
date: 1618154950
title: "aws glue, TLDR Pages"
description: "aws glue, CLI for AWS Glue."
categories: "common"
---
> Defines the public endpoint for the AWS Glue service.

> More information: <https://docs.aws.amazon.com/cli/latest/reference/glue/>.

- List jobs:

```bash
aws glue list-jobs
```

- Start a job:

```bash
aws glue start-job-run --job-name job_name
```

- Start running a workflow:

```bash
aws glue start-workflow-run --name workflow_name
```

- List triggers:

```bash
aws glue list-triggers
```

- Start a trigger:

```bash
aws glue start-trigger --name trigger_name
```

- Create a dev endpoint:

```bash
aws glue create-dev-endpoint --endpoint-name name --role-arn role_arn_used_by_endpoint
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | remove index.html from more information links where posible | 2021-04-11T17:29:10 | [1e2f4f202a9e](https://github.com/tldr-pages/tldr/commit/1e2f4f202a9e7827b670bd2db5d1cb776316df06)
[ahonarmand](mailto:72367678+ahonarmand@users.noreply.github.com) | aws-glue: add page (#4740) | 2020-10-24T14:40:49 | [18c35024fa00](https://github.com/tldr-pages/tldr/commit/18c35024fa007410d7b235ac66ee041f6493973c)

