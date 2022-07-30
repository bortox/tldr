---
author: ['bl-ue', 'Antoine Méausoone', 'Agniva De Sarker']
date: 1621541621
title: "kustomize"
description: "kustomize, Kustomize is a tool to easily deploy resources for Kubernetes."
categories: "common"
---
> More information: <https://github.com/kubernetes-sigs/kustomize>.

- Create kustomization file with resources and namespace:

```bash
kustomize create --resources deployment.yaml,service.yaml --namespace staging
```

- Build kustomization file and deploy it with `kubectl`:

```bash
kustomize build . | kubectl apply -f -
```

- Set an image in the kustomization file:

```bash
kustomize edit set image busybox=alpine:3.6
```

- Search for Kubernetes resources in the current directory to be added to the kustomization file:

```bash
kustomize create --autodetect
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | kustomize: make minor improvements (#3409) | 2019-10-13T13:47:00 | [0d048d2074f2](https://github.com/tldr-pages/tldr/commit/0d048d2074f2aa71912ecbb92ac0dfc9c3c69d9b)
[Antoine Méausoone](mailto:Ameausoone@users.noreply.github.com) | kustomize: add page (#3360) | 2019-10-10T13:44:51 | [2e5b3d01ebad](https://github.com/tldr-pages/tldr/commit/2e5b3d01ebadae3ec8652ebfdf7de81d39568364)

