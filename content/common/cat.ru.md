---
author: ['Dario Vladović', 'marchersimon', 'NikonP']
date: 1617292466
title: "cat, TLDR Pages"
description: "cat, Выводит и объединяет файлы."
categories: "common"
---
> Больше информации: <https://www.gnu.org/software/coreutils/cat>.

- Выводит содержимое файла:

```bash
cat файл
```

- Объединяет несколька файлов в один:

```bash
cat файл1 файл2 > итоговый_файл
```

- Добавляет несколько файлов в конец файла:

```bash
cat файл1 файл2 >> итоговый_файл
```

- Выводит содержимое файла с нумерацией строк:

```bash
cat -n файл
```

- Показывает все непечатные символы и пробелы (с префиксом `M-` для не-ASCII символов):

```bash
cat -v -t -e файл
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cat: change more information link (#5551) | 2021-03-30T12:31:55 | [3d97ba7785c1](https://github.com/tldr-pages/tldr/commit/3d97ba7785c175e55c9c9ac06f1f20b08837ea5d)
[NikonP](mailto:podgorny.nikon@yandex.ru) | cat: add Russian translation | 2020-10-19T19:38:47 | [984158c44b8e](https://github.com/tldr-pages/tldr/commit/984158c44b8e1fd33b9d5bbe579af23ae5cf9c67)

