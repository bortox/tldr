---
author: ['Furkan']
date: 1634756728
title: "trivy, TLDR Pages"
description: "trivy, Scanner for vulnerabilities in container images, file systems, and Git repositories, as well as for configuration issues."
categories: "common"
---
> More information: <https://github.com/aquasecurity/trivy>.

- Scan an image:

```bash
trivy image image:tag
```

- Scan the filesystem for vulnerabilities and misconfigurations:

```bash
trivy fs --security-checks vuln,config path/to/project_directory
```

- Scan a directory for misconfigurations:

```bash
trivy config path/to/iac_directory
```

- Generate output with a SARIF template:

```bash
trivy image --format template --template "@sarif.tpl" -o path/to/report.sarif image:tag
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Furkan](mailto:furkan.turkal@trendyol.com) | trivy: add page | 2021-10-20T21:05:28 | [6bd678160978](https://github.com/tldr-pages/tldr/commit/6bd6781609786a3055df1598ef8fa0fe7bb41208)

