---
author: ['gcagle3']
date: 1641814921
title: "terragrunt, TLDR Pages"
description: "terragrunt, Keep your Terraform CLI arguments DRY."
categories: "common"
---
> More information: <https://terragrunt.gruntwork.io>.

- Generate and show an execution plan:

```bash
terragrunt plan
```

- Build or change infrastructure:

```bash
terragrunt apply
```

- Show current deployment (from state):

```bash
terragrunt show
```

- Show module output values:

```bash
terragrunt output
```

- Destroy Terraform-managed infrastructure:

```bash
terragrunt destroy
```

- Build or change infrastructure from a tree of Terragrunt modules (stack):

```bash
terragrunt run-all apply
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[gcagle3](mailto:81821730+gcagle3@users.noreply.github.com) | terragrunt: add page (#7619) | 2022-01-10T12:42:01 | [a39a1fce8bb3](https://github.com/tldr-pages/tldr/commit/a39a1fce8bb3188dec2b10ea3feed2be622315bd)

