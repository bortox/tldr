---
author: ['Anton Khlynovskiy', 'Irina', 'bl-ue', 'marchersimon']
date: 1634106377
title: "7zr, TLDR Pages"
description: "7zr, Архиватор файлов с высокой степенью сжатия."
categories: "common"
---
> То же, что и `7z`, но поддерживает только файлы `.7z`.

> Больше информации: <https://www.7-zip.org>.

- Архивировать ([a]rchive) файл или папку:

```bash
7zr a путь/до/архива.7z путь/до/файла_или_папки
```

- Зашифровать существующий архив (включая имена файлов):

```bash
7zr a путь/до/зашифрованного_архива.7z -pпароль -mhe=on путь/до/архива.7z
```

- Распаковать (e[x]tract) существующий архив, сохраняя оригинальную структуру папок:

```bash
7zr x путь/до/архива.7z
```

- Распаковать (e[x]tract) архив в нужную папку:

```bash
7zr x путь/до/архива.7z -oпуть/до/папки
```

- Распаковать (e[x]tract) архив в stdout:

```bash
7zr x путь/до/архива.7z -so
```

- Вывести ([l]ist) содержимое архива:

```bash
7zr l путь/до/архива.7z
```

- Вывести список всех доступных типов архивов:

```bash
7zr i
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Irina](mailto:91758930+iridacea@users.noreply.github.com) | *: refresh Russian translation (#6850) | 2021-10-13T08:26:17 | [639b2e4e10c7](https://github.com/tldr-pages/tldr/commit/639b2e4e10c73c8014036c302192e4faa51e5279)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Anton Khlynovskiy](mailto:subzey@gmail.com) | 7z, 7za, 7zr: add Russian translation (#4792) | 2020-10-24T14:38:19 | [7e27042512b4](https://github.com/tldr-pages/tldr/commit/7e27042512b48792c6a287ee5b4562e3fd917f37)

