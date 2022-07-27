---
author: ['Ivan Aracki', 'Lucas Gabriel Schneider', 'Seth Falco', 'bl-ue']
date: 1629050349
title: "kops, TLDR Pages"
description: "kops, Create, destroy, upgrade and maintain Kubernetes clusters from the command-line."
categories: "common"
---
> More information: <https://github.com/kubernetes/kops/>.

- Create a cluster from the configuration specification:

```bash
kops create cluster -f cluster_name.yaml
```

- Create a new ssh public key:

```bash
kops create secret sshpublickey key_name -i ~/.ssh/id_rsa.pub
```

- Export the cluster configuration to the `~/.kube/config` file:

```bash
kops export kubecfg cluster_name
```

- Get the cluster configuration as YAML:

```bash
kops get cluster cluster_name -o yaml
```

- Delete a cluster:

```bash
kops delete cluster cluster_name --yes
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | kops: add page (#3149) | 2019-06-30T13:02:25 | [276b65fc65a1](https://github.com/tldr-pages/tldr/commit/276b65fc65a1b4f0b5fd14078e2a9b4fbaaa8b13)

