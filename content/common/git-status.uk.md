---
author: ['burlakvo']
date: 1633295537
title: "git status, TLDR Pages"
description: "git status, Показує зміни до файлів у Git-репозиторії."
categories: "common"
---
> Списки змінених, доданих та видалених файлів в порівнянні до поточного зареєстрованого коміту.

> Більше інформації: <https://git-scm.com/docs/git-status>.

- Показує змінені файли які ще не додані до коміту:

```bash
git status
```

- Виводить інформацію у стислому ([s]hort) форматі:

```bash
git status -s
```

- Виводить інформацію без неконтрольованих файлів:

```bash
git status --untracked-files=no
```

- Виводить інформацію у стислому ([s]hort) форматі разом з інформацією про гілку ([b]ranch):

```bash
git status -sb
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[burlakvo](mailto:48330319+burlakvo@users.noreply.github.com) | git, git-add, git-status: add Ukrainian translation (#6745) | 2021-10-03T23:12:17 | [dcb79e9c1b0c](https://github.com/tldr-pages/tldr/commit/dcb79e9c1b0c9bf5145b99e82902ee1e0817ebc1)

