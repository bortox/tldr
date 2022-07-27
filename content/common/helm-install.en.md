---
author: ['Simon Dahlbacka']
date: 1635474745
title: "helm install, TLDR Pages"
description: "helm install, Install a helm chart."
categories: "common"
---
> More information: <https://helm.sh/docs/intro/using_helm/#helm-install-installing-a-package>.

- Install a helm chart:

```bash
helm install name repository_name/chart_name
```

- Install a helm chart from an unpacked chart directory:

```bash
helm install name path/to/source_directory
```

- Install a helm chart from a URL:

```bash
helm install package_name https://example.com/charts/packagename-1.2.3.tgz
```

- Install a helm chart and generate a name:

```bash
helm install repository_name/chart_name --generate-name
```

- Perform a dry run:

```bash
helm install name repository_name/chart_name --dry-run
```

- Install a helm chart with custom values:

```bash
helm install name repository_name/chart_name --set parameter1=value1,parameter2=value2
```

- Install a helm chart passing a custom values file:

```bash
helm install name repository_name/chart_name --values path/to/values.yaml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Simon Dahlbacka](mailto:simon.dahlbacka@ecraft.com) | helm-install: add page (#6995) | 2021-10-29T04:32:25 | [331cfea5fa34](https://github.com/tldr-pages/tldr/commit/331cfea5fa340003c4e87607507b8ef3107ff88f)

