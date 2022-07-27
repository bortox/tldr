---
author: ['Kirill Stryaponov']
date: 1643706301
title: "cwebp, TLDR Pages"
description: "cwebp, Сжимает файл изображения в формат WebP."
categories: "common"
---
> Больше информации: <https://developers.google.com/speed/webp/docs/cwebp>.

- Сжать WebP со стандартными настройками (q = 75) с сохранением в выходной файл:

```bash
cwebp путь/к/изображению -o путь/к/результату.webp
```

- Сжать WebP с наилучшим качеством и наибольшим размером файла:

```bash
cwebp путь/к/изображению -o путь/к/результату.webp -q 100
```

- Сжать WebP с наихудшим качеством и наименьшим размером файла:

```bash
cwebp путь/к/изображению -o путь/к/результату.webp -q 0
```

- Сжать WebP с изменением размера изображения:

```bash
cwebp путь/к/изображению -o путь/к/результату.webp -resize width height
```

- Сжать WebP с удалением информации о прозрачности:

```bash
cwebp путь/к/изображению -o путь/к/результату.webp -noalpha
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Kirill Stryaponov](mailto:stryaponoff@gmail.com) | cwebp: add page (#7722) * cwebp: add page * cwebp: add russian translation * cwebp: update descriptions * cwebp: update Russian [...] | 2022-02-01T10:05:01 | [3e8b075813d2](https://github.com/tldr-pages/tldr/commit/3e8b075813d2ba46324422e6e3b2f133706293b1)

