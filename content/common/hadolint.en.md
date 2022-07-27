---
author: ['Michael Bianchi']
date: 1603909588
title: "hadolint, TLDR Pages"
description: "hadolint, Dockerfile linter."
categories: "common"
---
> More information: <https://github.com/hadolint/hadolint>.

- Lint a Dockerfile:

```bash
hadolint path/to/Dockerfile
```

- Lint a Dockerfile, displaying the output in JSON format:

```bash
hadolint --format json path/to/Dockerfile
```

- Lint a Dockerfile, displaying the output in a specific format:

```bash
hadolint --format tty|json|checkstyle|codeclimate|codacy path/to/Dockerfile
```

- Lint a Dockerfile ignoring specific rules:

```bash
hadolint --ignore DL3006 --ignore DL3008 path/to/Dockerfile
```

- Lint multiple Dockerfiles using specific trusted registries:

```bash
hadolint --trusted-registry docker.io --trusted-registry example.com:5000 path/to/Dockerfile path/to/another/Dockerfile
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Michael Bianchi](mailto:michaeldbianchi@gmail.com) | hadolint: add page (#4782) | 2020-10-28T19:26:28 | [cf8b401aeb8d](https://github.com/tldr-pages/tldr/commit/cf8b401aeb8d36883cf58d22621b34d1964d207d)

