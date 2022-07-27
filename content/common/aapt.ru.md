---
author: ['Ryzhehvost', 'bl-ue', 'marchersimon']
date: 1633112881
title: "aapt, TLDR Pages"
description: "aapt, Утилита для упаковки ресурсов для Android."
categories: "common"
---
> Компилирует и упаковывает ресурсы приложений Android.

> Больше информации: <https://elinux.org/Android_aapt>.

- Вывести список файлов содержащихся в APK-архиве:

```bash
aapt list путь/до/приложения.apk
```

- Отобразить мета-данные приложения (версия, разрешения, и т.д.):

```bash
aapt dump badging путь/до/приложения.apk
```

- Создать новый APK-архив с файлами из указанной папки:

```bash
aapt package -F путь/до/приложения.apk путь/до/папки
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | aapt to ag: add Russian translation (#4882) | 2020-11-16T19:18:22 | [c2420e8db02a](https://github.com/tldr-pages/tldr/commit/c2420e8db02a6c24eb77d06c2b6394b8b6936421)

