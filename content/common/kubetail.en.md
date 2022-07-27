---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Ivan Aracki']
date: 1559788968
title: "kubetail, TLDR Pages"
description: "kubetail, Utility to tail multiple Kubernetes pod logs at the same time."
categories: "common"
---
> More information: <https://github.com/johanhaleby/kubetail>.

- Tail the logs of multiple pods (whose name starts with "my_app") in one go:

```bash
kubetail my_app
```

- Tail only a specific container from multiple pods:

```bash
kubetail my_app -c my_container
```

- To tail multiple containers from multiple pods:

```bash
kubetail my_app -c my_container_1 -c my_container_2
```

- To tail multiple applications at the same time separate them by comma:

```bash
kubetail my_app_1,my_app_2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | kubetail: add link to homepage | 2019-06-06T04:42:48 | [7339d980b2b9](https://github.com/tldr-pages/tldr/commit/7339d980b2b94e88f5479f6c83ad44ef521feaa3)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: fixed typos (#2871) | 2019-04-06T14:34:03 | [9abddffd09d3](https://github.com/tldr-pages/tldr/commit/9abddffd09d33dba8c1e022085f7aa4e7ca6ce1b)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | kubetail: add page (#2623) | 2018-12-01T22:19:05 | [36c6b4018135](https://github.com/tldr-pages/tldr/commit/36c6b4018135b7996364854071cfa294ffc298ea)

