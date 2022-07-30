---
author: ['Elijah Shackelford']
date: 1602540388
title: "aws ec2"
description: "aws ec2, CLI for AWS EC2."
categories: "common"
---
> Provides secure and resizable computing capacity in the AWS cloud to enable faster development and deployment of applications.

> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/ec2/index.html>.

- Show list of all available EC2 commands:

```bash
aws ec2 help
```

- Show help for specific EC2 subcommand:

```bash
aws ec2 subcommand help
```

- Display information about a specific instance:

```bash
aws ec2 describe-instances --instance-ids instance_id
```

- Display information about all instances:

```bash
aws ec2 describe-instances
```

- Display information about all EC2 volumes:

```bash
aws ec2 describe-volumes
```

- Delete an EC2 volume:

```bash
aws ec2 delete-volume --volume-id volume_id
```

- Create a snapshot from an EC2 volume:

```bash
aws ec2 create-snapshot --volume-id volume_id
```

- List available AMIs (Amazon Machine Images):

```bash
aws ec2 describe-images
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Elijah Shackelford](mailto:33649649+eshack94@users.noreply.github.com) | aws ec2: Add entry (#4661) | 2020-10-13T00:06:28 | [6b248c8b6e6d](https://github.com/tldr-pages/tldr/commit/6b248c8b6e6d6a2a8474cdd92e4fde1d424de58a)

