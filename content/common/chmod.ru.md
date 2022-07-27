---
author: ['Dario Vladović', 'Irina', 'marchersimon', 'Bodyhealer']
date: 1634106377
title: "chmod, TLDR Pages"
description: "chmod, Изменить права доступа файлу или папке."
categories: "common"
---
> Больше информации: <https://www.gnu.org/software/coreutils/chmod>.

- Дать пользователю ([u]ser), который владеет файлом, права на его исполнение (e[x]ecute):

```bash
chmod u+x файл
```

- Дать права пользователю ([u]ser) права чтения ([r]ead) и записи ([w]rite) в файл/папку:

```bash
chmod u+rw файл_или_папка
```

- Убрать права на исполнение (e[x]ecute) у группы ([g]roup):

```bash
chmod g-x файл
```

- Дать всем ([a]ll) пользователям права на чтение ([r]ead) и исполнение (e[x]ecute):

```bash
chmod a+rx файл
```

- Дать другим ([o]thers) (не из группы владельцев файла) такие же права, как и у группы ([g]roup):

```bash
chmod o=g файл
```

- Убрать все права у других ([o]thers):

```bash
chmod o= файл
```

- Изменить права рекурсивно, дав группе ([g]roup) и другим ([o]thers) возможность записи ([w]rite) в папку:

```bash
chmod -R g+w,o+w папка
```

- Рекурсивно дать для всех ([a]ll) пользователей права на чтение ([r]ead) файлов и права на исполнение (e[X]ecute) поддиректорий внутри указанной директории:

```bash
chmod -R a+rX папка
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Irina](mailto:91758930+iridacea@users.noreply.github.com) | *: refresh Russian translation (#6850) | 2021-10-13T08:26:17 | [639b2e4e10c7](https://github.com/tldr-pages/tldr/commit/639b2e4e10c73c8014036c302192e4faa51e5279)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chmod: change more information link (#5547) | 2021-03-29T22:28:18 | [db38dff0e9db](https://github.com/tldr-pages/tldr/commit/db38dff0e9db1d880e7406df340d16509470fbbb)
[Bodyhealer](mailto:Bodyhealer@users.noreply.github.com) | adb*, chmod, weasyprint: add Russian translation (#4905) | 2020-11-04T20:37:23 | [7820f750851c](https://github.com/tldr-pages/tldr/commit/7820f750851cde6f46c1fce7e37432b0e0dde0f3)

