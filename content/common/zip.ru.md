---
author: ['Anton Khlynovskiy', 'marchersimon']
date: 1633112881
title: "zip"
description: "zip, Упаковывает и сжимает (архивирует) файлы в файл zip."
categories: "common"
---
> Больше информации: <https://manned.org/zip>.

- Упаковать и сжать папку и её содержимое, рекурсивно ([r]ecursive):

```bash
zip -r архив.zip /путь/до/папки
```

- Исключить (e[x]clude) ненужные файлы из добавляемых в сжатый архив:

```bash
zip -r архив.zip путь/до/папки -x путь/который/исключаем
```

- Архивировать папку и её содержимое с самым сильным [9] сжатием:

```bash
zip -r -9 архив.zip /путь/до/папки
```

- Упаковать и сжать несколько папок и файлов:

```bash
zip -r архив.zip /путь/до/папки1 /путь/до/папки2 /путь/до/файла
```

- Создать зашифрованный архив (пользователя спросят пароль):

```bash
zip -e -r архив.zip путь/до/папки
```

- Добавить файлы в существующий файл zip:

```bash
zip архив.zip путь/до/файла
```

- Удалить файлы из существующего файла zip:

```bash
zip -d архив.zip "папка/*.tmp"
```

- Архивировать папку и её содержимое, разделив ([s]plit) файл zip на несколько томов (например, кусками по 3 ГБ):

```bash
zip -r -s 3g архив.zip путь/до/папки
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Anton Khlynovskiy](mailto:subzey@gmail.com) | zip, unzip: add Russian translation (#4777) | 2020-10-24T14:18:12 | [dcd183b3a0e7](https://github.com/tldr-pages/tldr/commit/dcd183b3a0e71dc1b79b8eb85a4bb133ea71d8d9)

