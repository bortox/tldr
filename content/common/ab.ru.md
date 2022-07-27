---
author: ['Ryzhehvost', 'bl-ue']
date: 1615671899
title: "ab, TLDR Pages"
description: "ab, Утилита бенчмаркинга Apache. Самая простая утилита для проведения нагрузочного тестирования."
categories: "common"
---
> Больше информации: <https://httpd.apache.org/docs/current/programs/ab.html>.

- Запустить 100 запросов HTTP GET по заданному URL:

```bash
ab -n 100 url
```

- Запустить 100 запросов HTTP GET, обрабатывая до 10 одновременно, по заданному URL:

```bash
ab -n 100 -c 10 url
```

- Использовать постоянное соединение (keep-alive):

```bash
ab -k url
```

- Задать максимальное число секунд, которое можно затратить на бенчмаркинг:

```bash
ab -t 60 url
```

- Запустить 100 запросов HTTP POST по заданному URL, используя в качестве полезной нагрузки JSON из файла:

```bash
ab -n 100 -T application/json -p путь/до/файла.json url
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | ab: update grammar; update link (#5433) | 2021-03-13T22:44:59 | [8f2ed246f761](https://github.com/tldr-pages/tldr/commit/8f2ed246f7614df6e815b9eefae053a0f64df920)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | aapt to ag: add Russian translation (#4882) | 2020-11-16T19:18:22 | [c2420e8db02a](https://github.com/tldr-pages/tldr/commit/c2420e8db02a6c24eb77d06c2b6394b8b6936421)

