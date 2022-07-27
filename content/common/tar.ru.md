---
author: ['Matthew Peveler', "Robby O'Connor", 'Bodyhealer']
date: 1618508857
title: "tar, TLDR Pages"
description: "tar, Утилита архивирования."
categories: "common"
---
> Обычно используется в сочетании с методом сжатия, такими как gzip или bzip2.

> Больше информации: <https://www.gnu.org/software/tar>.

- Создать архив из файлов:

```bash
tar cf целевой.tar файл1 файл2 файл3
```

- Создать gzip архив:

```bash
tar czf целевой.tar.gz файл1 файл2 файл3
```

- Создать gzip архив из деректории, используя относительные пути:

```bash
tar czf целевой.tar.gz -C путь/до/папки .
```

- Извлечь (сжатый) архив в текущую папку:

```bash
tar xf исходный.tar[.gz|.bz2|.xz]
```

- Извлечь (сжатый) архив в указанную папку:

```bash
tar xf исходный.tar[.gz|.bz2|.xz] -C папка
```

- Создать сжатый архив, использую суффикс архива для определения программы сжатия:

```bash
tar caf целевой.tar.xz файл1 файл2 файл3
```

- Вывести список содержимого tar файла:

```bash
tar tvf исходный.tar
```

- Извлечь файлы удовлетворяющие шаблону:

```bash
tar xf исходный.tar --wildcards "*.html"
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Matthew Peveler](mailto:matt.peveler@gmail.com) | tar: remove extra example (#5762) Signed-off-by: Matthew Peveler <matt.peveler@gmail.com> | 2021-04-15T19:47:37 | [acf0ccef24e6](https://github.com/tldr-pages/tldr/commit/acf0ccef24e6004da67037978106a931023d78de)
[Robby O'Connor](mailto:rob@oconnor.ninja) | tar: fix bzip to bzip2 in command description (#5264) | 2021-02-13T04:53:30 | [5cd65c2850e0](https://github.com/tldr-pages/tldr/commit/5cd65c2850e0f3186af032337f596dbb7c5be79a)
[Bodyhealer](mailto:Bodyhealer@users.noreply.github.com) | tar: add Russian translation (#4535) | 2020-10-06T20:04:40 | [08286f624294](https://github.com/tldr-pages/tldr/commit/08286f624294dc9f348d1ec202658a8be042fcdf)

