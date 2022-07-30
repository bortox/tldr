---
author: ['burlakvo']
date: 1633879582
title: "git commit-tree"
description: "git commit-tree, Низькорівнева утиліта для створення об'єктів комітів."
categories: "common"
---
> Дивись також: `git commit`.

> Більше інформації: <https://git-scm.com/docs/git-commit-tree>.

- Створює об'єкт коміту із певним повідомленням:

```bash
git commit-tree tree -m "повідомлення"
```

- Створює об'єкт коміту читаючи повідомлення з файлу (використовуй `-` для читання зі стандартного введення):

```bash
git commit-tree tree -F шлях/до/файлу
```

- Створює GPG-підписаний об'єкт коміту:

```bash
git commit-tree tree -m "повідомлення" --gpg-sign
```

- Створює об'єкт коміту із певним батьківським об'єктом коміту:

```bash
git commit-tree tree -m "повідомлення" -p sha_батьківського_коміту
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[burlakvo](mailto:48330319+burlakvo@users.noreply.github.com) | git-commit*: add Ukrainian translation (#6847) | 2021-10-10T17:26:22 | [e717d057ab3c](https://github.com/tldr-pages/tldr/commit/e717d057ab3ca35640cbb9a95193b062785b0237)

