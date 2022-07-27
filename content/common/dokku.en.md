---
author: ['Waldir Pimenta', 'siavashsoleymani', 'pxgamer', 'Igor Shubovych']
date: 1603796471
title: "dokku, TLDR Pages"
description: "dokku, Docker powered mini-Heroku (PaaS)."
categories: "common"
---
> Easily deploy multiple apps to your server in different languages using a single `git-push` command.

> More information: <https://github.com/dokku/dokku>.

- List running apps:

```bash
dokku apps
```

- Create an app:

```bash
dokku apps:create app_name
```

- Remove an app:

```bash
dokku apps:destroy app_name
```

- Install plugin:

```bash
dokku plugin:install full_repo_url
```

- Link database to an app:

```bash
dokku db:link db_name app_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[siavashsoleymani](mailto:siavash.solimanii@yahoo.com) | dokku: fix typo | 2020-10-27T12:01:11 | [36eac699880c](https://github.com/tldr-pages/tldr/commit/36eac699880cf39ae2e9905b1992a420aefd9a67)
[pxgamer](mailto:owzie123@gmail.com) | dokku: add link to homepage | 2019-06-09T06:54:24 | [c32e5d99b3d5](https://github.com/tldr-pages/tldr/commit/c32e5d99b3d51c97496e2d050df8520d245077f5)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | dokku: lowercase heading, per project guidelines | 2016-09-08T05:33:35 | [ff14ef08b619](https://github.com/tldr-pages/tldr/commit/ff14ef08b619978edc68efafde1e0bf00ab4f99b)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Fix #417. Add Dokku command (kudos to @Cri5) | 2016-01-09T19:40:06 | [5aaf64b32681](https://github.com/tldr-pages/tldr/commit/5aaf64b3268105cfca24f82919bb49d18fe5acad)

