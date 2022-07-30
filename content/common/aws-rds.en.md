---
author: ['258204']
date: 1633575229
title: "aws rds"
description: "aws rds, CLI for AWS Relational Database Service."
categories: "common"
---
> Create and manage relational databases.

> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/rds/index.html>.

- Show help for specific RDS subcommand:

```bash
aws rds subcommand help
```

- Stop instance:

```bash
aws rds stop-db-instance --db-instance-identifier instance_identifier
```

- Start instance:

```bash
aws rds start-db-instance --db-instance-identifier instance_identifier
```

- Modify an RDS instance:

```bash
aws rds modify-db-instance --db-instance-identifier instance_identifier parameters --apply-immediately
```

- Apply updates to an RDS instance:

```bash
aws rds apply-pending-maintenance-action --resource-identifier database_arn --apply-action system-update --opt-in-type immediate
```

- Change an instance identifier:

```bash
aws rds modify-db-instance --db-instance-identifier old_instance_identifier --new-db-instance-identifier new_instance_identifier
```

- Reboot an instance:

```bash
aws rds reboot-db-instance --db-instance-identifier instance_identifier
```

- Delete an instance:

```bash
aws rds delete-db-instance --db-instance-identifier instance_identifier --final-db-snapshot-identifier snapshot_identifier --delete-automated-backups
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[258204](mailto:71364336+258204@users.noreply.github.com) | aws-rds: add page (#6547) | 2021-10-07T04:53:49 | [5826e30a7a5e](https://github.com/tldr-pages/tldr/commit/5826e30a7a5e5cb321a6dc4959b62823804e2228)

