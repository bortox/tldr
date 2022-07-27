---
author: ['Ryzhehvost']
date: 1603906263
title: "dotnet build, TLDR Pages"
description: "dotnet build, Собирает приложение .NET и все его зависимости."
categories: "common"
---
> Больше информации: <https://docs.microsoft.com/dotnet/core/tools/dotnet-build>.

- Скомпилировать проект или решение в текущей директории:

```bash
dotnet build
```

- Скомпилировать проект или решение .NET в режиме debug:

```bash
dotnet build путь/до/проекта_или_решения
```

- Скомпилировать в режиме release:

```bash
dotnet build --configuration Release
```

- Скомпилировать без восстановления зависимостей:

```bash
dotnet build --no-restore
```

- Скомпилировать с заданным уровнем детализации выводимой информации:

```bash
dotnet build --verbosity quiet|minimal|normal|detailed|diagnostic
```

- Скомпилировать для заданной среды исполнения:

```bash
dotnet build --runtime идентификатор_среды_исполения
```

- Указать целевую папку:

```bash
dotnet build --output путь/до/папки
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | dotnet-build: fix compile in release mode example (#4809) | 2020-10-28T18:31:03 | [81f0b337e1fe](https://github.com/tldr-pages/tldr/commit/81f0b337e1feae71e1f0a6c69b711a2db9e7f466)

