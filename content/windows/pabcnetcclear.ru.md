---
author: ['Emily Grace Seville']
date: 1636917047
title: "pabcnetcclear"
description: "pabcnetcclear, Предобрабатывает и компилирует PascalABC.NET исходные файлы."
categories: "windows"
---
> Больше информации: <http://pascalabc.net>.

- Компилирует исходный файл в запускаемое приложение с тем же именем:

```bash
pabcnetcclear путь/до/файла.pas
```

- Компилирует исходный файл в запускаемое приложение с тем же именем вместе с отладочной информацией:

```bash
pabcnetcclear /Debug:1 путь/до/файла.pas
```

- Разрешает искать модули в указанной папке во время компиляции исходного файла в запускаемое приложение с тем же именем:

```bash
pabcnetcclear /SearchDir:путь/до/папки путь/до/файла.pas
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | pabcnetcclear: add page (#7412) | 2021-11-14T20:10:47 | [0dfceab76bd6](https://github.com/tldr-pages/tldr/commit/0dfceab76bd62a5b5d34bc7c4979250f4ca19a7e)

