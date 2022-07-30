---
author: ['lucas schneider', 'Rodolphe Lemasquerier']
date: 1610111394
title: "transcrypt"
description: "transcrypt, Transparently encrypt files within a Git repository."
categories: "common"
---
> More information: <https://github.com/elasticdog/transcrypt>.

- Initialize an unconfigured repository:

```bash
transcrypt
```

- List the currently encrypted files:

```bash
git ls-crypt
```

- Display the credentials of a configured repository:

```bash
transcrypt --display
```

- Initialize and decrypt a fresh clone of a configured repository:

```bash
transcrypt --cipher=cipher
```

- Rekey to change the encryption cipher or password:

```bash
transcrypt --rekey
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Rodolphe Lemasquerier](mailto:rodolphel@bam.tech) | transcrypt: add page (#3952) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-04-05T22:06:18 | [acb8af9307f7](https://github.com/tldr-pages/tldr/commit/acb8af9307f7c84135721a4575ee41f755fc93f5)

