---
author: ['Emily Grace Seville']
date: 1648358251
title: "mcs"
description: "mcs, Mono компилятор C#."
categories: "common"
---
> Больше информации: <https://manned.org/mcs.1>.

- Скомпилировать указанные файлы:

```bash
mcs путь/к/входному_файлу1.cs путь/к/входному_файлу2.cs ...
```

- Указать имя выходной программы:

```bash
mcs -out:путь/к/файлу.exe путь/к/входному_файлу1.cs путь/к/входному_файлу2.cs ...
```

- Указать тип выходной программы:

```bash
mcs -target:exe|winexe|library|module путь/к/входному_файлу1.cs путь/к/входному_файлу2.cs ...
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | mcs: add Russian translation (#7908) | 2022-03-27T07:17:31 | [8d3613e0a033](https://github.com/tldr-pages/tldr/commit/8d3613e0a0337b99d66447e13d81c1fa22e00f90)

