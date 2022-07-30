---
author: ['burlakvo']
date: 1633879582
title: "git commit"
description: "git commit, Комітить файли до репозиторію."
categories: "common"
---
> Більше інформації: <https://git-scm.com/docs/git-commit>.

- Комітить індексовані файли до репозиторію з повідомленням:

```bash
git commit -m "повідомлення"
```

- Комітить індексовані файли з повідомленням, що прочитано у файлі:

```bash
git commit --file шлях/до/файлу_з_повідомленням
```

- Автоматично індексує усі змінені файли і комітить їх з повідомленням:

```bash
git commit -a -m "повідомлення"
```

- Комітить індексовані файли та підписує ([S]ign) їх ключем GPG, що визначений у `~/.gitconfig`:

```bash
git commit -S -m "повідомлення"
```

- Оновлює останній коміт додаючи до нього щойно індексовані зміни, також змінює геш коміту:

```bash
git commit --amend
```

- Комітить тільки певні (вже індексовані) файли:

```bash
git commit шлях/до/файлу1 шлях/до/файлу2
```

- Створює коміт, навіть якщо немає жодного індексованого файлу:

```bash
git commit -m "повідомлення" --allow-empty
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[burlakvo](mailto:48330319+burlakvo@users.noreply.github.com) | git-commit*: add Ukrainian translation (#6847) | 2021-10-10T17:26:22 | [e717d057ab3c](https://github.com/tldr-pages/tldr/commit/e717d057ab3ca35640cbb9a95193b062785b0237)

