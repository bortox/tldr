---
author: ['Emily Grace Seville']
date: 1650118956
title: "cut, TLDR Pages"
description: "cut, Вырезать поля из стандартного ввода или файлов."
categories: "common"
---
> Больше информации: <https://www.gnu.org/software/coreutils/cut>.

- Вывести указанный диапазон символов/полей каждой строки (`--{{characters|fields}}={{1|1,10|1-10|1-|-10}}` далее обозначается как `{{диапазон}}`):

```bash
команда | cut --characters|fields=1|1,10|1-10|1-|-10
```

- Вывести диапазон каждой строки с указанным разделителем:

```bash
команда | cut --delimiter="," диапазон
```

- Вывести диапазон каждой строки указанного файла:

```bash
cut диапазон путь/к/файлу
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | cut: add Russian translation (#7940) * Add russian translations for cut * Add pipes where stdin required | 2022-04-16T16:22:36 | [609ad2632629](https://github.com/tldr-pages/tldr/commit/609ad2632629bfaaa47a4f27a73b92448e51b186)

