---
author: ['Ilya Pantsyr']
date: 1650439019
title: "dokku"
description: "dokku, Міні-Heroku на основі Docker (PaaS)."
categories: "common"
---
> Легко розгортає кілька програм на власному сервері різними мовами за допомогою однієї команди `git-push`.

> Більше інформації: <https://github.com/dokku/dokku>.

- Показати запущені програми:

```bash
dokku apps
```

- Створити програму:

```bash
dokku apps:create ім'я_програми
```

- Видалити програму:

```bash
dokku apps:destroy ім'я_програми
```

- Встановити плагін:

```bash
dokku plugin:install повний_url_на_репозиторій
```

- Зв'язати базу даних із програмою:

```bash
dokku db:link ім'я_бази_даних ім'я_програми
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ilya Pantsyr](mailto:panilyau@gmail.com) | dog, dokku: add Ukrainian translation (#8036) | 2022-04-20T09:16:59 | [87781641f6db](https://github.com/tldr-pages/tldr/commit/87781641f6db3a24be43f38f158f1ed92aa1b26d)

