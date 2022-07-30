---
author: ['bl-ue', 'Ivan Aracki']
date: 1621541621
title: "k8s-unused-secret-detector"
description: "k8s-unused-secret-detector, Command-line interface tool for detecting unused Kubernetes secrets."
categories: "common"
---
> More information: <https://github.com/dtan4/k8s-unused-secret-detector>.

- Detect unused secrets:

```bash
k8s-unused-secret-detector
```

- Detect unused secrets in a specific namespace:

```bash
k8s-unused-secret-detector -n namespace
```

- Delete unused secrets in a specific namespace:

```bash
k8s-unused-secret-detector -n namespace | kubectl delete secret -n namespace
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | k8s-unused-secret-detector: add page (#3342) | 2019-10-07T15:29:25 | [1898be912de0](https://github.com/tldr-pages/tldr/commit/1898be912de04b43b6f13b426422c72d0e0b5091)

