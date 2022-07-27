---
author: ['Ryzhehvost', 'Bodyhealer']
date: 1605550702
title: "adb install, TLDR Pages"
description: "adb install, Android Debug Bridge Install: Установка пакетов на эмулятор Android или подключенное устройство Android."
categories: "common"
---
> Больше информации: <https://developer.android.com/studio/command-line/adb>.

- Установить приложение Android на эмулятор/устройство:

```bash
adb install путь/до/файла.apk
```

- Переустановить существующее приложение, оставив его данные:

```bash
adb install -r путь/до/файла.apk
```

- Дать все разрешения, перечисленные в манифесте приложения:

```bash
adb install -g путь/до/файла.apk
```

- Быстрое обновление установленного пакета путём обновления только тех частей APK, которые изменились:

```bash
adb install --fastdeploy путь/до/файла.apk
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | aapt to ag: add Russian translation (#4882) | 2020-11-16T19:18:22 | [c2420e8db02a](https://github.com/tldr-pages/tldr/commit/c2420e8db02a6c24eb77d06c2b6394b8b6936421)
[Bodyhealer](mailto:Bodyhealer@users.noreply.github.com) | adb*, chmod, weasyprint: add Russian translation (#4905) | 2020-11-04T20:37:23 | [7820f750851c](https://github.com/tldr-pages/tldr/commit/7820f750851cde6f46c1fce7e37432b0e0dde0f3)

