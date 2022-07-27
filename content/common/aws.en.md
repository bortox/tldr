---
author: ['bl-ue', 'pxgamer', 'Aracki', 'Guido Lena Cota', 'Seth Falco', 'marchersimon', 'Cody']
date: 1631521281
title: "aws, TLDR Pages"
description: "aws, The official CLI tool for Amazon Web Services."
categories: "common"
---
> Some subcommands such as `aws s3` have their own usage documentation.

> More information: <https://aws.amazon.com/cli>.

- Configure the AWS Command-line:

```bash
aws configure wizard
```

- Configure the AWS Command-line using SSO:

```bash
aws configure sso
```

- See help text for the AWS command:

```bash
aws command help
```

- Get the caller identity (used to troubleshoot permissions):

```bash
aws sts get-caller-identity
```

- List AWS resources in a region and output in YAML:

```bash
aws dynamodb list-tables --region us-east-1 --output yaml
```

- Use auto prompt to help with a command:

```bash
aws iam create-user --cli-auto-prompt
```

- Get an interactive wizard for an AWS resource:

```bash
aws dynamodb wizard new_table
```

- Generate a JSON CLI Skeleton (useful for infrastructure as code):

```bash
aws dynamodb update-table --generate-cli-skeleton
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Cody](mailto:30978270+codypenta@users.noreply.github.com) | aws: upgrade to CLIv2 (#3892) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-03-06T22:13:10 | [454fe1cfbbca](https://github.com/tldr-pages/tldr/commit/454fe1cfbbca46848e0dfac25efd8b3e67521bf8)
[pxgamer](mailto:owzie123@gmail.com) | aws: add link to homepage | 2019-06-09T18:53:49 | [8eddd030c07d](https://github.com/tldr-pages/tldr/commit/8eddd030c07d56fb6fe370574839e43e3be5b78a)
[Aracki](mailto:aracki.ivan@gmail.com) | aws: update desc | 2018-12-19T05:58:32 | [38eddd7035fd](https://github.com/tldr-pages/tldr/commit/38eddd7035fd2295fd1870aff1bb203168474266)
[Aracki](mailto:aracki.ivan@gmail.com) | aws: add page | 2018-12-19T05:58:32 | [f28ec36045fa](https://github.com/tldr-pages/tldr/commit/f28ec36045fa6ea8e6774c258b32140870dde26c)

