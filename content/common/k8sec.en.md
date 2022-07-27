---
author: ['bl-ue', 'Ivan Aracki']
date: 1621541621
title: "k8sec, TLDR Pages"
description: "k8sec, Command-line interface tool to manage Kubernetes secrets."
categories: "common"
---
> More information: <https://github.com/dtan4/k8sec>.

- List all secrets:

```bash
k8sec list
```

- List a specific secret as a base64-encoded string:

```bash
k8sec list secret_name --base64
```

- Set a secret's value:

```bash
k8sec set secret_name key=value
```

- Set a base64-encoded value:

```bash
k8sec set --base64 secret_name key=encoded_value
```

- Unset a secret:

```bash
k8sec unset secret_name
```

- Load secrets from a file:

```bash
k8sec load -f path/to/file secret_name
```

- Dump secrets to a file:

```bash
k8sec dump -f path/to/file secret_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | k8sec: fix replacement of theses (#3378) | 2019-10-13T14:37:51 | [5484964a7617](https://github.com/tldr-pages/tldr/commit/5484964a76174e3829512ba1bfcab595feeb64d3)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | k8sec: add page (#3341) | 2019-10-10T20:42:43 | [d2520560a8df](https://github.com/tldr-pages/tldr/commit/d2520560a8dfafacd219e359e1fa021b19f9fe04)

