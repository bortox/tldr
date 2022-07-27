---
author: ['Ryzhehvost', 'Bodyhealer']
date: 1605550702
title: "adb reverse, TLDR Pages"
description: "adb reverse, Android Debug Bridge Reverse: обратное соединение от эмулятора Android или подключенного устройства Android."
categories: "common"
---
> Больше информации: <https://developer.android.com/studio/command-line/adb>.

- Вывести список всех обратных соединений от эмуляторов и устройств:

```bash
adb reverse --list
```

- Создать обратное соединение по TCP-порту от эмулятора или устройства до localhost:

```bash
adb reverse tcp:удалённый_порт tcp:локальный_порт
```

- Удалить обратное соединение из эмулятора или устройства:

```bash
adb reverse --remove tcp:удалённый_порт
```

- Удалить все обратные соединения на всех эмуляторах и устройствах:

```bash
adb reverse --remove-all
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | aapt to ag: add Russian translation (#4882) | 2020-11-16T19:18:22 | [c2420e8db02a](https://github.com/tldr-pages/tldr/commit/c2420e8db02a6c24eb77d06c2b6394b8b6936421)
[Bodyhealer](mailto:Bodyhealer@users.noreply.github.com) | adb*, chmod, weasyprint: add Russian translation (#4905) | 2020-11-04T20:37:23 | [7820f750851c](https://github.com/tldr-pages/tldr/commit/7820f750851cde6f46c1fce7e37432b0e0dde0f3)

