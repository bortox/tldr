---
author: ['Ryzhehvost', 'Irina', 'Bodyhealer']
date: 1633553117
title: "adb, TLDR Pages"
description: "adb, Android Debug Bridge: управление запущенным эмулятором Android или подключенным устройством Android."
categories: "common"
---
> Некоторые подкоманды, такие как `adb shell`, имеют собственную документацию по использованию.

> Больше информации: <https://developer.android.com/studio/command-line/adb>.

- Проверить, запущен ли процесс сервера adb и запустить его:

```bash
adb start-server
```

- Завершить процесс сервера adb:

```bash
adb kill-server
```

- Запустить удалённую оболочку на целевом эмуляторе/устройстве:

```bash
adb shell
```

- Установить приложение Android на эмуляторе/устройстве:

```bash
adb install -r путь/до/файла.apk
```

- Скопировать файл/папку с целевого устройства:

```bash
adb pull путь/до/папки_или_файла_на_устройстве путь/до/локальной_папки
```

- Скопировать файл/папку на целевое устройство:

```bash
adb push путь/до/локального_файла_или_папки путь/до/целевой_папки_на_устройстве
```

- Вывести список подключенных устройств:

```bash
adb devices
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Irina](mailto:91758930+iridacea@users.noreply.github.com) | add reference to sub-commands in base pages in Russian | 2021-10-06T22:45:17 | [61c54c271896](https://github.com/tldr-pages/tldr/commit/61c54c271896bc8e442e68585b8d8cd2ce8929ce)
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | aapt to ag: add Russian translation (#4882) | 2020-11-16T19:18:22 | [c2420e8db02a](https://github.com/tldr-pages/tldr/commit/c2420e8db02a6c24eb77d06c2b6394b8b6936421)
[Bodyhealer](mailto:Bodyhealer@users.noreply.github.com) | adb*, chmod, weasyprint: add Russian translation (#4905) | 2020-11-04T20:37:23 | [7820f750851c](https://github.com/tldr-pages/tldr/commit/7820f750851cde6f46c1fce7e37432b0e0dde0f3)

