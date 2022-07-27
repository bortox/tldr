---
author: ['Crystal Fletcher', 'bl-ue', 'marchersimon', 'lucas schneider']
date: 1625253777
title: "vela, TLDR Pages"
description: "vela, Command-line tools for the Vela pipeline."
categories: "common"
---
> More information: <https://go-vela.github.io/docs/reference/cli/>.

- Trigger a pipeline to run from a Git branch, commit or tag:

```bash
vela add deployment --org organization --repo repository_name --target environment --ref branch|commit|refs/tags/git_tag --description "deploy_description"
```

- List deployments for a repository:

```bash
vela get deployment --org organization --repo repository_name
```

- Inspect a specific deployment:

```bash
vela view deployment --org organization --repo repository_name --deployment deployment_number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Crystal Fletcher](mailto:sporeluc@gmail.com) | vela: add page (#4942) | 2020-11-16T19:17:53 | [a3f1b62b1085](https://github.com/tldr-pages/tldr/commit/a3f1b62b1085f13217f93a1573f4a2d5e2224fba)

