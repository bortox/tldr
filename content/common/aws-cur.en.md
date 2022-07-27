---
author: ['258204', 'caduvieira']
date: 1633518566
title: "aws cur, TLDR Pages"
description: "aws cur, Create, query, and delete AWS usage report definitions."
categories: "common"
---
> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/cur/index.html>.

- Create an AWS cost and usage report definition from a JSON file:

```bash
aws cur put-report-definition --report-definition file://path/to/report_definition.json
```

- List usage report definitions defined for the logged in account:

```bash
aws cur describe-report-definitions
```

- Delete a usage report definition:

```bash
aws cur --region aws_region delete-report-definition --report-name report
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[caduvieira](mailto:3831408+caduvieira@users.noreply.github.com) | aws-cur, aws-secretsmanager: add pt_BR translation (#6782) | 2021-10-06T13:09:26 | [02bb89332e0e](https://github.com/tldr-pages/tldr/commit/02bb89332e0e93a0f389de87567b10e50d5a63a1)
[258204](mailto:71364336+258204@users.noreply.github.com) | aws-cur: add page (#6133) | 2021-06-23T16:34:14 | [e55d089237d6](https://github.com/tldr-pages/tldr/commit/e55d089237d66217391249432086d831fb3d0148)

