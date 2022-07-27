---
author: ['Ryzhehvost', 'bl-ue']
date: 1610462196
title: "ag, TLDR Pages"
description: "ag, The Silver Searcher. Аналог ack, но имеет цель быть быстрее."
categories: "common"
---
> Больше информации: <https://github.com/ggreer/the_silver_searcher>.

- Найти файлы, содержащие "foo", и вывести подходящие строки в контексте:

```bash
ag foo
```

- Найти файлы, содержащие "foo", в заданной папке:

```bash
ag foo путь/до/папки
```

- Найти файлы, содержащие "foo", но вывести только имена файлов:

```bash
ag -l foo
```

- Найти файлы, содержащие "FOO", независимо от регистра, и вывести только совпадения, а не строки целиком:

```bash
ag -i -o FOO
```

- Найти "foo" в файлах, у которых в имени есть "bar":

```bash
ag foo -G bar
```

- Найти файлы, содержимое которых совпадает с регулярным выражением:

```bash
ag '^ba(r|z)$'
```

- Найти файлы, у которых имя совпадает с "foo":

```bash
ag -g foo
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | aapt to ag: add Russian translation (#4882) | 2020-11-16T19:18:22 | [c2420e8db02a](https://github.com/tldr-pages/tldr/commit/c2420e8db02a6c24eb77d06c2b6394b8b6936421)

