---
author: ['Owen Voke']
date: 1610989849
title: "lambo new, TLDR Pages"
description: "lambo new, A super-powered `laravel new` for Laravel and Valet."
categories: "common"
---
> More information: <https://github.com/tighten/lambo>.

- Create a new Laravel application:

```bash
lambo new app_name
```

- Install the application in a specific path:

```bash
lambo new --path=path/to/directory app_name
```

- Include authentication scaffolding:

```bash
lambo new --auth app_name
```

- Include a specific frontend:

```bash
lambo new --vue|bootstrap|react app_name
```

- Install npm dependencies after the project has been created:

```bash
lambo new --node app_name
```

- Create a Valet site after the project has been created:

```bash
lambo new --link app_name
```

- Create a new MySQL database with the same name as the project:

```bash
lambo new --create-db --dbuser=user --dbpassword=password app_name
```

- Open a specific editor after the project has been created:

```bash
lambo new --editor="editor" app_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | lambo, lambo-new: add page (#5139) | 2021-01-18T18:10:49 | [d022d1f1d4a5](https://github.com/tldr-pages/tldr/commit/d022d1f1d4a526b7929a89249700345ad8484b4a)

