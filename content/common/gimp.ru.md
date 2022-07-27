---
author: ['Emily Grace Seville']
date: 1648358450
title: "gimp, TLDR Pages"
description: "gimp, GNU программа для работы с изображениями."
categories: "common"
---
> Смотрите также: `krita`.

> Больше информации: <https://docs.gimp.org/en/gimp-fire-up.html#gimp-concepts-running-command-line>.

- Запустить GIMP:

```bash
gimp
```

- Запустить без заставки:

```bash
gimp --no-splash
```

- Открыть указанные файлы:

```bash
gimp путь/к/изображению1 путь/к/изображению2 ...
```

- Запустить новый инстанс, даже если один уже запущен:

```bash
gimp --new-instance
```

- Вывести ошибки и предупреждения в консоль, вместо отображения их в диалоговом окне:

```bash
gimp --console-messages
```

- Включить обработчики сигналов отладки:

```bash
gimp --debug-handlers
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | gimp: add Russian translation (#7907) | 2022-03-27T07:20:50 | [f63fedd5857c](https://github.com/tldr-pages/tldr/commit/f63fedd5857ccfd4317e99f405d0748343b7f1eb)

