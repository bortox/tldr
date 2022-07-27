---
author: ['258204']
date: 1624435215
title: "aws ecr, TLDR Pages"
description: "aws ecr, Push, pull, and manage container images."
categories: "common"
---
> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/ecr/index.html>.

- Authenticate Docker with the default registry (username is AWS):

```bash
aws ecr get-login-password --region region | docker login --username AWS --password-stdin aws_account_id.dkr.ecr.region.amazonaws.com
```

- Create a repository:

```bash
aws ecr create-repository --repository-name repository --image-scanning-configuration scanOnPush=true|false --region region
```

- Tag a local image for ECR:

```bash
docker tag container_name:tag aws_account_id.dkr.ecr.region.amazonaws.com/container_name:tag
```

- Push an image to a repository:

```bash
docker push aws_account_id.dkr.ecr.region.amazonaws.com/container_name:tag
```

- Pull an image from a repository:

```bash
docker pull aws_account_id.dkr.ecr.region.amazonaws.com/container_name:tag
```

- Delete an image from a repository:

```bash
aws ecr batch-delete-image  --repository-name repository --image-ids imageTag=latest
```

- Delete a repository:

```bash
aws ecr delete-repository --repository-name repository --force
```

- List images within a repository:

```bash
aws ecr list-images --repository-name repository
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[258204](mailto:71364336+258204@users.noreply.github.com) | aws-ecr: add page (#6134) | 2021-06-23T10:00:15 | [1d376950964b](https://github.com/tldr-pages/tldr/commit/1d376950964b1628e38dde7f52dec65c794e18f6)

