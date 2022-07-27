---
author: ['Giorgio Lasala']
date: 1633831438
title: "dotnet ef, TLDR Pages"
description: "dotnet ef, Perform design-time development tasks for Entity Framework Core."
categories: "common"
---
> More information: <https://docs.microsoft.com/ef/core/cli/dotnet>.

- Update the database to a specified migration:

```bash
dotnet ef database update migration
```

- Drop the database:

```bash
dotnet ef database drop
```

- List available `DbContext` types:

```bash
dotnet ef dbcontext list
```

- Generate code for a `DbContext` and entity types for a database:

```bash
dotnet ef dbcontext scaffold connection_string provider
```

- Add a new migration:

```bash
dotnet ef migrations add name
```

- Remove the last migration, rolling back the code changes that were done for the latest migration:

```bash
dotnet ef migrations remove
```

- List available migrations:

```bash
dotnet ef migrations list
```

- Generate a SQL script from migrations range:

```bash
dotnet ef migrations script from_migration to_migration
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Giorgio Lasala](mailto:salem84@users.noreply.github.com) | dotnet-ef: add page (#6799) | 2021-10-10T04:03:58 | [30d336163de2](https://github.com/tldr-pages/tldr/commit/30d336163de24d6f496a93a398d2c014ce1a6e3a)

