---
author: ['burlakvo']
date: 1633295537
title: "git add, TLDR Pages"
description: "git add, Додає змінені файли до індексу."
categories: "common"
---
> Більше інформації: <https://git-scm.com/docs/git-add>.

- Додає змінені файли до індексу:

```bash
git add шлях/до/файлу
```

- Додає усі файли (контрольовані та неконтрольовані):

```bash
git add -A
```

- Додає тільки ті файли, що вже контрольовані:

```bash
git add -u
```

- Додає й ті файли, що ігноруються:

```bash
git add -f
```

- Інтерактивно індексує частини файлів:

```bash
git add -p
```

- Інтерактивно індексує частини вказаного файлу:

```bash
git add -p шлях/до/файлу
```

- Інтерактивно індексує файл:

```bash
git add -i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[burlakvo](mailto:48330319+burlakvo@users.noreply.github.com) | git, git-add, git-status: add Ukrainian translation (#6745) | 2021-10-03T23:12:17 | [dcb79e9c1b0c](https://github.com/tldr-pages/tldr/commit/dcb79e9c1b0c9bf5145b99e82902ee1e0817ebc1)

