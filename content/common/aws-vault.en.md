---
author: ['Anay Nayak']
date: 1601887973
title: "aws-vault"
description: "aws-vault, A vault for securely storing and accessing AWS credentials in development environments."
categories: "common"
---
> More information: <https://github.com/99designs/aws-vault>.

- Add credentials to the secure keystore:

```bash
aws-vault add profile
```

- Execute a command with AWS credentials in the environment:

```bash
aws-vault exec profile -- aws s3 ls
```

- Open a browser window and login to the AWS Console:

```bash
aws-vault login profile
```

- List profiles, along with their credentials and sessions:

```bash
aws-vault list
```

- Rotate AWS credentials:

```bash
aws-vault rotate profile
```

- Remove credentials from the secure keystore:

```bash
aws-vault remove profile
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anay Nayak](mailto:anaynayak@users.noreply.github.com) | aws-vault: add page (#4471) | 2020-10-05T10:52:53 | [d68b0a4198d3](https://github.com/tldr-pages/tldr/commit/d68b0a4198d37f2e1910d858ebb641486466e71a)

