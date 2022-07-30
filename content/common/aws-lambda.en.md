---
author: ['honarmand-io', 'marchersimon']
date: 1618154950
title: "aws lambda"
description: "aws lambda, CLI for AWS lambda."
categories: "common"
---
> More information: <https://docs.aws.amazon.com/cli/latest/reference/lambda/>.

- Run a function:

```bash
aws lambda invoke --function-name name path/to/response.json
```

- Run a function with an input payload in JSON format:

```bash
aws lambda invoke --function-name name --payload json path/to/response.json
```

- List functions:

```bash
aws lambda list-functions
```

- Display the configuration of a function:

```bash
aws lambda get-function-configuration --function-name name
```

- List function aliases:

```bash
aws lambda list-aliases --function-name name
```

- Display the reserved concurrency configuration for a function:

```bash
aws lambda get-function-concurrency --function-name name
```

- List which AWS services can invoke the function:

```bash
aws lambda get-policy --function-name name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | remove index.html from more information links where posible | 2021-04-11T17:29:10 | [1e2f4f202a9e](https://github.com/tldr-pages/tldr/commit/1e2f4f202a9e7827b670bd2db5d1cb776316df06)
[honarmand-io](mailto:72320803+honarmand-io@users.noreply.github.com) | aws-lambda: add page (#4774) | 2020-10-28T19:12:01 | [4e011efcbe09](https://github.com/tldr-pages/tldr/commit/4e011efcbe09fb3484b2a8809f978ebc8c85c6af)

