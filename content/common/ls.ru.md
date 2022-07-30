---
author: ['Axel Navarro', 'Irina', 'Dario Vladović', 'NikonP', 'marchersimon']
date: 1634106377
title: "ls"
description: "ls, Вывод содержимого каталога."
categories: "common"
---
> Больше информации: <https://www.gnu.org/software/coreutils/ls>.

- Список файлов по одному в строке:

```bash
ls -1
```

- Список всех файлов, включая скрытые:

```bash
ls -a
```

- Список всех файлов с добавлением в конце `/` к именам директорий:

```bash
ls -F
```

- Подробный список с выводом разрешений, владельцев, размера и даты изменения всех файлов:

```bash
ls -la
```

- Подробный список с выводом размера файла в удобочитаемых единицах (КиБ, МиБ, ГиБ):

```bash
ls -lh
```

- Подробный список, отсортированный по размеру файлов (по убыванию):

```bash
ls -lS
```

- Подробный список, отсортированный по дате изменения файла (сначала более старые):

```bash
ls -ltr
```

- Список только директорий:

```bash
ls -d */
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Irina](mailto:91758930+iridacea@users.noreply.github.com) | *: refresh Russian translation (#6850) | 2021-10-13T08:26:17 | [639b2e4e10c7](https://github.com/tldr-pages/tldr/commit/639b2e4e10c73c8014036c302192e4faa51e5279)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ls: add link (#5561) | 2021-03-30T09:12:42 | [a0e1beab9bd7](https://github.com/tldr-pages/tldr/commit/a0e1beab9bd704de488fefaca86d0c5e20a7a03b)
[Axel Navarro](mailto:navarroaxel@gmail.com) | ls: fix size units in example description (#5451) | 2021-03-15T20:57:50 | [8402bf0fa60e](https://github.com/tldr-pages/tldr/commit/8402bf0fa60e2e1d94b94c75aeceba8ed40fc409)
[NikonP](mailto:podgorny.nikon@yandex.ru) | ls: add Russian translation (#4595) | 2020-10-09T19:03:49 | [7360e26b4032](https://github.com/tldr-pages/tldr/commit/7360e26b40323ca89d2a40691d39a12d0ab2ce6f)

