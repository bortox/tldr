---
author: ['Anton Khlynovskiy', 'Lucas Gabriel Schneider', 'lincc']
date: 1643487459
title: "unzip"
description: "unzip, Извлекает сжатые файлы из архива zip."
categories: "common"
---
> Больше информации: <https://manned.org/unzip>.

- Распаковать файл(ы) zip (для нескольких файлов укажите пути через пробел):

```bash
unzip архив(ы)
```

- Распаковать файл(ы) по нужному пути:

```bash
unzip архив(ы) -d /путь/куда/положить/извлечённый_файл(ы)
```

- Вывести список файлов в архиве zip, не распаковывая их:

```bash
unzip -l архив.zip
```

- Извлечь содержимое файла в stdout вместе с именами распакованных файлов:

```bash
unzip -c архив.zip
```

- Распаковать архив zip, который был создан на windows и содержит не-ascii имена файлов (напр. кириллица):

```bash
unzip -O gbk архив.zip
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Anton Khlynovskiy](mailto:subzey@gmail.com) | zip, unzip: add Russian translation (#4777) | 2020-10-24T14:18:12 | [dcd183b3a0e7](https://github.com/tldr-pages/tldr/commit/dcd183b3a0e71dc1b79b8eb85a4bb133ea71d8d9)

