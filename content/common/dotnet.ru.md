---
author: ['Ryzhehvost', 'Irina']
date: 1633553117
title: "dotnet, TLDR Pages"
description: "dotnet, Кросс-платформенная утилита командной строки .NET для .NET Core."
categories: "common"
---
> Некоторые подкоманды, такие как `dotnet build`, имеют собственную документацию по использованию.

> Больше информации: <https://docs.microsoft.com/dotnet/core/tools>.

- Инициализировать новый проект .NET:

```bash
dotnet new короткое_имя_шаблона
```

- Восстановить пакеты nuget:

```bash
dotnet restore
```

- Собрать и запустить проект .NET в текущей папке:

```bash
dotnet run
```

- Запустить собранное приложение .NET (требуется только среда исполнения, для остальных команд требуется установленный .NET Core SDK):

```bash
dotnet путь/до/приложения.dll
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Irina](mailto:91758930+iridacea@users.noreply.github.com) | add reference to sub-commands in base pages in Russian | 2021-10-06T22:45:17 | [61c54c271896](https://github.com/tldr-pages/tldr/commit/61c54c271896bc8e442e68585b8d8cd2ce8929ce)
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | dotnet: add Russian translation (#4801) | 2020-10-24T14:49:07 | [386a62de6f8d](https://github.com/tldr-pages/tldr/commit/386a62de6f8d47b5a8195393148ee29ae95abd34)

