---
author: ['bl-ue', 'Ryzhehvost']
date: 1610462196
title: "act"
description: "act, Запуск GitHub Actions локально с использованием Docker."
categories: "common"
---
> Больше информации: <https://github.com/nektos/act>.

- Вывести список доступных actions:

```bash
act -l
```

- Запустить событие по умолчанию:

```bash
act
```

- Запустить заданное событие:

```bash
act тип_события
```

- Запустить заданный action:

```bash
act -a action_id
```

- Не производить реальный запуск actions (пробный прогон):

```bash
act -n
```

- Отображать расширенный лог:

```bash
act -v
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | aapt to ag: add Russian translation (#4882) | 2020-11-16T19:18:22 | [c2420e8db02a](https://github.com/tldr-pages/tldr/commit/c2420e8db02a6c24eb77d06c2b6394b8b6936421)

