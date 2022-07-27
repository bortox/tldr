---
author: ['Ryzhehvost']
date: 1603543875
title: "dotnet restore, TLDR Pages"
description: "dotnet restore, Восстанавливает зависимости и утилиты для проекта .NET."
categories: "common"
---
> Больше информации: <https://docs.microsoft.com/dotnet/core/tools/dotnet-restore>.

- Восстановить зависимости для проекта или решения .NET в текущей директории:

```bash
dotnet restore
```

- Восстановить зависимости для проекта или решенияs .NET по заданному пути:

```bash
dotnet restore путь/до/проекта_или_решения
```

- Восстановить зависимости без кеширования HTTP-запросов:

```bash
dotnet restore --no-cache
```

- Принудительно восстановить все зависимости, даже если предыдущее восстановление было успешным:

```bash
dotnet restore --force
```

- Восстановить зависимости, считая что ошибки источника пакетов это предупреждения:

```bash
dotnet restore --ignore-failed-sources
```

- Восстановить зависимости, используя заданный уровень детализации выводимой информации:

```bash
dotnet restore --verbosity quiet|minimal|normal|detailed|diagnostic
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | dotnet-restore: add Russian translation (#4803) | 2020-10-24T14:51:15 | [8ab2df04d24d](https://github.com/tldr-pages/tldr/commit/8ab2df04d24d1eb172481dd76dd60e6453a6849f)

