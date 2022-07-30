---
author: ['burlakvo']
date: 1633879582
title: "git commit-graph"
description: "git commit-graph, Записує та перевіряє файл графіку комітів Git."
categories: "common"
---
> Більше інформації: <https://git-scm.com/docs/git-commit-graph>.

- Записує файл графіку комітів для спакованих комітів у локальній директорії `.git`:

```bash
git commit-graph write
```

- Записує файл графіку комітів, що містить набір усіх досяжних комітів:

```bash
git show-ref --hash | git commit-graph write --stdin-commits
```

- Записує файл графіку комітів, що містить усі коміти у поточному файлі графіку комітів разом з тими, до яких можна отримати доступ з `HEAD`:

```bash
git rev-parse HEAD | git commit-graph write --stdin-commits --append
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[burlakvo](mailto:48330319+burlakvo@users.noreply.github.com) | git-commit*: add Ukrainian translation (#6847) | 2021-10-10T17:26:22 | [e717d057ab3c](https://github.com/tldr-pages/tldr/commit/e717d057ab3ca35640cbb9a95193b062785b0237)

