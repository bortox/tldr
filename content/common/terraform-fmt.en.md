---
author: ['Nelson Figueroa']
date: 1586116978
title: "terraform fmt"
description: "terraform fmt, Format configuration according to Terraform language style conventions."
categories: "common"
---
> More information: <https://www.terraform.io/docs/commands/fmt.html>.

- Format the configuration in the current directory:

```bash
terraform fmt
```

- Format the configuration in the current directory and subdirectories:

```bash
terraform fmt -recursive
```

- Display diffs of formatting changes:

```bash
terraform fmt -diff
```

- Do not list files that were formatted to stdout:

```bash
terraform fmt -list=false
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | terraform-fmt: add page (#3958) | 2020-04-05T22:02:58 | [10f6f2a68ed7](https://github.com/tldr-pages/tldr/commit/10f6f2a68ed725fa6bb77f4e9493eec8784164fc)

