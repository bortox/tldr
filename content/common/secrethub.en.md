---
author: ['Simon Barendse']
date: 1581380640
title: "secrethub, TLDR Pages"
description: "secrethub, A tool to keep secrets out of config files."
categories: "common"
---
> More information: <https://secrethub.io>.

- Print a secret to stdout:

```bash
secrethub read path/to/secret
```

- Generate a random value and store it as a new or updated secret:

```bash
secrethub generate path/to/secret
```

- Store a value from the clipboard as a new or updated secret:

```bash
secrethub write --clip path/to/secret
```

- Store a value supplied on stdin as a new or updated secret:

```bash
echo "secret_value" | secrethub write path/to/secret
```

- Audit a repository or secret:

```bash
secrethub audit path/to/repo_or_secret
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Simon Barendse](mailto:SimonBarendse@users.noreply.github.com) | secrethub: clarify versioning (#3847) | 2020-02-11T01:24:00 | [ed97d6dc9ecd](https://github.com/tldr-pages/tldr/commit/ed97d6dc9ecd46a0dc43cc1b65b8330971e86ca8)
[Simon Barendse](mailto:SimonBarendse@users.noreply.github.com) | secrethub: add page (#3794) * secrethub: add page * Use token syntax for piping a secret value to write Co-authored-by: [...] | 2020-01-27T14:12:54 | [ac0e7625a220](https://github.com/tldr-pages/tldr/commit/ac0e7625a220be278a3c0cad70b7635840f6d460)

