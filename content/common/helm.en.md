---
author: ['Vidhi Gupta', 'Marco Bonelli', 'Lucas Gabriel Schneider', 'Simon Dahlbacka']
date: 1635474745
title: "helm"
description: "helm, Helm is a package manager for Kubernetes."
categories: "common"
---
> Some subcommands such as `helm install` have their own usage documentation.

> More information: <https://helm.sh/>.

- Create a helm chart:

```bash
helm create chart_name
```

- Add a new helm repository:

```bash
helm repo add repository_name
```

- List helm repositories:

```bash
helm repo list
```

- Update helm repositories:

```bash
helm repo update
```

- Delete a helm repository:

```bash
helm repo remove repository_name
```

- Install a helm chart:

```bash
helm install name repository_name/chart_name
```

- Download helm chart as a tar archive:

```bash
helm get chart_release_name
```

- Update helm dependencies:

```bash
helm dependency update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Simon Dahlbacka](mailto:simon.dahlbacka@ecraft.com) | helm-install: add page (#6995) | 2021-10-29T04:32:25 | [331cfea5fa34](https://github.com/tldr-pages/tldr/commit/331cfea5fa340003c4e87607507b8ef3107ff88f)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3025) | 2019-05-14T18:06:07 | [5514f773e2df](https://github.com/tldr-pages/tldr/commit/5514f773e2dfcd02ab6bc87c7e02fa8f7fbe2f25)
[Vidhi Gupta](mailto:vidhigupta0494@gmail.com) | helm: add page (#2349) | 2018-10-17T22:41:08 | [f49d0f79654c](https://github.com/tldr-pages/tldr/commit/f49d0f79654c9463cf8e99f6ab53af2cd4466731)

