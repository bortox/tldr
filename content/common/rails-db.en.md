---
author: ['Nelson Figueroa', 'Lucas Gabriel Schneider', 'Kyle']
date: 1628770875
title: "rails db, TLDR Pages"
description: "rails db, Various database-related subcommands for Ruby on Rails."
categories: "common"
---
> More information: <https://guides.rubyonrails.org/command_line.html>.

- Create databases, load the schema, and initialize with seed data:

```bash
rails db:setup
```

- Access the database console:

```bash
rails db
```

- Create the databases defined in the current environment:

```bash
rails db:create
```

- Destroy the databases defined in the current environment:

```bash
rails db:drop
```

- Run pending migrations:

```bash
rails db:migrate
```

- View the status of each migration file:

```bash
rails db:migrate:status
```

- Rollback the last migration:

```bash
rails db:rollback
```

- Fill the current database with data defined in `db/seeds.rb`:

```bash
rails db:seed
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | rails-db: add more information link (#6338) | 2021-08-12T14:21:15 | [1d5e2d17ddce](https://github.com/tldr-pages/tldr/commit/1d5e2d17ddceb68e94c3de90c31c85b4ab3834c5)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | rails-db: add page (#3070) | 2019-06-04T16:54:38 | [f44b2ad3fa6a](https://github.com/tldr-pages/tldr/commit/f44b2ad3fa6a10c4742278d985217075205c3696)

