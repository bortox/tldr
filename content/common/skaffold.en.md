---
author: ['Ivan Aracki', 'Marco Bonelli']
date: 1559564381
title: "skaffold"
description: "skaffold, A tool that facilitates continuous development for Kubernetes applications."
categories: "common"
---
> More information: <https://skaffold.dev>.

- Build the artifacts:

```bash
skaffold build -f skaffold.yaml
```

- Build and deploy your app every time your code changes:

```bash
skaffold dev -f skaffold.yaml
```

- Run a pipeline file:

```bash
skaffold run -f skaffold.yaml
```

- Run a diagnostic on Skaffold:

```bash
skaffold diagnose -f skaffold.yaml
```

- Deploy the artifacts:

```bash
skaffold deploy -f skaffold.yaml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | skaffold: add page (#2909) | 2019-04-15T14:11:57 | [4e113b6a7fbc](https://github.com/tldr-pages/tldr/commit/4e113b6a7fbc37bc46f05a834fa3d28ffaead5e6)

