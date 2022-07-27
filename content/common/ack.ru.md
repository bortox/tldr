---
author: ['Ryzhehvost', 'Irina', 'bl-ue', 'marchersimon']
date: 1634106377
title: "ack, TLDR Pages"
description: "ack, Утилита для поиска, подобная grep, оптимизировання для программистов."
categories: "common"
---
> Смотри также: `rg`, которая гораздо быстрее.

> Больше информации: <https://beyondgrep.com/documentation>.

- Найти файлы, содержащие строку или регулярное выражение, рекурсивно в текущей директории:

```bash
ack "шаблон_поиска"
```

- Искать по шаблону без учёта регистра:

```bash
ack --ignore-case "шаблон_поиска"
```

- Искать строки, соответствующие шаблону, печатая только ([o]nly) совпавший текст, а не остальную часть строки:

```bash
ack -o "шаблон_поиска"
```

- Ограничить поиск только файлами определённого типа:

```bash
ack --type=ruby "шаблон_поиска"
```

- Не искать в файлах определённого типа:

```bash
ack --type=noruby "шаблон_поиска"
```

- Подсчитать общее количество найденных совпадений:

```bash
ack --count --no-filename "шаблон_поиска"
```

- Вывести только имена файлов и количество совпадений для каждого файла:

```bash
ack --count --files-with-matches "шаблон_поиска"
```

- Вывести все значения, которые можно использовать с `--type`:

```bash
ack --help-types
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Irina](mailto:91758930+iridacea@users.noreply.github.com) | *: refresh Russian translation (#6850) | 2021-10-13T08:26:17 | [639b2e4e10c7](https://github.com/tldr-pages/tldr/commit/639b2e4e10c73c8014036c302192e4faa51e5279)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | aapt to ag: add Russian translation (#4882) | 2020-11-16T19:18:22 | [c2420e8db02a](https://github.com/tldr-pages/tldr/commit/c2420e8db02a6c24eb77d06c2b6394b8b6936421)

