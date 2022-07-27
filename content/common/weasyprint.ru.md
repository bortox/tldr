---
author: ['bl-ue', 'Bodyhealer']
date: 1621541621
title: "weasyprint, TLDR Pages"
description: "weasyprint, Переводить HTML в PDF или PNG."
categories: "common"
---
> Больше информации: <https://weasyprint.org/>.

- Перевести HTML файл в PDF:

```bash
weasyprint путь/до/входного.html путь/до/выходного.pdf
```

- Перевести HTML файл в PNG, включая дополнительные пользовательские таблицы стилей:

```bash
weasyprint путь/до/входного.html путь/до/выходного.png --stylesheet путь/до/таблицы-стилей.css
```

- При переводе выводить дополнительную отладочную информацию:

```bash
weasyprint путь/до/входного.html путь/до/выходного.pdf --verbose
```

- При выводе в PNG указать нестандартное разрешение:

```bash
weasyprint путь/до/входного.html путь/до/выходного.png --resolution 300
```

- Во входном HTML файле указать базовый URL для относительных URLs:

```bash
weasyprint путь/до/входного.html путь/до/выходного.png --base-url url_или_имя-файла
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Bodyhealer](mailto:Bodyhealer@users.noreply.github.com) | adb*, chmod, weasyprint: add Russian translation (#4905) | 2020-11-04T20:37:23 | [7820f750851c](https://github.com/tldr-pages/tldr/commit/7820f750851cde6f46c1fce7e37432b0e0dde0f3)

