---
author: ['psyashes']
date: 1636826314
title: "terraform plan"
description: "terraform plan, Generate and show Terraform execution plans."
categories: "common"
---
> More information: <https://www.terraform.io/docs/cli/commands/plan.html>.

- Generate and show the execution plan in the currently directory:

```bash
terraform plan
```

- Show a plan to destroy all remote objects that currently exist:

```bash
terraform plan -destroy
```

- Show a plan to update the Terraform state and output values:

```bash
terraform plan -refresh-only
```

- Specify values for input variables:

```bash
terraform plan -var 'name1=value1' -var 'name2=value2'
```

- Focus Terraform's attention on only a subset of resources:

```bash
terraform plan -target resource_type.resource_name[instance index]
```

- Output a plan as JSON:

```bash
terraform plan -json
```

- Write a plan to a specific file:

```bash
terraform plan -no-color > path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[psyashes](mailto:43512814+psyashes@users.noreply.github.com) | terraform-plan: add page (#7406) | 2021-11-13T18:58:34 | [93a23576ca2f](https://github.com/tldr-pages/tldr/commit/93a23576ca2f53c78154a402c6bcda9ef9bffdc9)

