---
author: ['Christian Wenz']
date: 1636233118
title: "dolt clone, TLDR Pages"
description: "dolt clone, Clone a repository into a new directory."
categories: "common"
---
> More information: <https://docs.dolthub.com/interfaces/cli#dolt-clone>.

- Clone an existing repository into a specific directory (defaults to the repository name):

```bash
dolt clone repository_url path/to/directory
```

- Clone an existing repository and add a specific remote (defaults to origin):

```bash
dolt clone --remote remote_name repository_url
```

- Clone an existing repository only fetching a specific branch (defaults to all branches):

```bash
dolt clone --branch branch_name repository_url
```

- Clone a repository, using an AWS region (uses the profile's default region if none is provided):

```bash
dolt clone --aws-region region_name repository_url
```

- Clone a repository, using an AWS credentials file:

```bash
dolt clone --aws-creds-file credentials_file repository_url
```

- Clone a repository, using an AWS credentials profile (uses the default profile if none is provided):

```bash
dolt clone --aws-creds-profile profile_name repository_url
```

- Clone a repository, using an AWS credentials type:

```bash
dolt clone --aws-creds-type credentials_type repository_url
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Christian Wenz](mailto:christian@wenz.org) | dolt-clone: add page (#7237) | 2021-11-06T22:11:58 | [bf6770280431](https://github.com/tldr-pages/tldr/commit/bf6770280431af83be0ea775c606063f46f595af)

