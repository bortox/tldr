---
author: ['Emily Grace Seville', 'marchersimon', 'Erik Bartels']
date: 1659075216
title: "jq"
description: "jq, Процессор JSON командной строки, использующий доменный язык."
categories: "common"
---
> Больше информации: <https://stedolan.github.io/jq/manual/>.

- Выполнить указанное выражение (вывести цветной и отформатированный json):

```bash
cat путь/к/файлу.json | jq '.'
```

- Выполнить указанный скрипт:

```bash
cat путь/к/файлу.json | jq --from-file путь/к/скрипту.jq
```

- Передать указанные агрументы:

```bash
cat путь/к/файлу.json | jq --arg "имя1" "значение1" --arg "имя2" "значение2" ... '. + $ARGS.named'
```

- Вывести указанные ключи:

```bash
cat путь/к/файлу.json | jq '.ключ1, .ключ2, ...'
```

- Вывести указанные элементы массива:

```bash
cat путь/к/файлу.json | jq '.[индекс1], .[индекс2], ...'
```

- Вывести все элементы массива/ключи объекта:

```bash
cat путь/к/файлу.json | jq '.[]'
```

- Добавить/удалить указанные ключи:

```bash
cat путь/к/файлу.json | jq '. +|- {"ключ1": "значение1", "ключ2": "значение2", ...}'
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Erik Bartels](mailto:eb@soundcloud.com) | jq: remove filename dangling quote (#8063) | 2022-04-30T09:07:02 | [61805c1a2557](https://github.com/tldr-pages/tldr/commit/61805c1a2557b6004374e0950f7d027b2a65020e)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | jq: update page (#7945) * Fix manual url * Replace all old examples with new ones: - executing expression/script - accessing [...] | 2022-04-13T03:45:18 | [f0dacdbd2098](https://github.com/tldr-pages/tldr/commit/f0dacdbd20986a8fef80179f94f120df3234928e)

