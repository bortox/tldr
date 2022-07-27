---
author: ['Ryzhehvost', 'Bodyhealer']
date: 1605550702
title: "adb shell, TLDR Pages"
description: "adb shell, Android Debug Bridge Shell: Запуск удалённой командной оболочки на эмуляторе Android или подключенном устройстве Android."
categories: "common"
---
> Больше информации: <https://developer.android.com/studio/command-line/adb>.

- Запустить удалённую интерактивную оболочку на эмуляторе или устройстве:

```bash
adb shell
```

- Получить все свойства от эмулятора или устройства:

```bash
adb shell getprop
```

- Вернуть всем разрешениям значение по умолчанию:

```bash
adb shell pm reset-permissions
```

- Отозвать опасные разрешения для приложения:

```bash
adb shell pm revoke пакет разрешения
```

- Вызвать событие клавиши:

```bash
adb shell input keyevent код_клавиши
```

- Очистить данные приложения на эмуляторе или устройстве:

```bash
adb shell pm clear пакет
```

- Запустить activity на эмуляторе или устройстве:

```bash
adb shell am start -n пакет/активность
```

- Запустить базовый activity на эмуляторе или устройстве:

```bash
adb shell am start -W -c android.intent.category.HOME -a android.intent.action.MAIN
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | aapt to ag: add Russian translation (#4882) | 2020-11-16T19:18:22 | [c2420e8db02a](https://github.com/tldr-pages/tldr/commit/c2420e8db02a6c24eb77d06c2b6394b8b6936421)
[Bodyhealer](mailto:Bodyhealer@users.noreply.github.com) | adb*, chmod, weasyprint: add Russian translation (#4905) | 2020-11-04T20:37:23 | [7820f750851c](https://github.com/tldr-pages/tldr/commit/7820f750851cde6f46c1fce7e37432b0e0dde0f3)

