---
author: ['Ryzhehvost']
date: 1603543980
title: "dotnet publish"
description: "dotnet publish, Публикует .NET-приложение и его зависимости в папку для развёртываения на целевой системе."
categories: "common"
---
> Больше информации: <https://docs.microsoft.com/dotnet/core/tools/dotnet-publish>.

- Скомпилировать проект .NET в режиме release:

```bash
dotnet publish --configuration Release путь/до/файла_проекта
```

- Опубликовать ваше приложение с заданной средой исполнения .NET Core:

```bash
dotnet publish --self-contained true --runtime идентификатор_среды_исполения путь/до/файла_проекта
```

- Упаковать приложение в один исполняемый файл для заданной платформы:

```bash
dotnet publish --runtime идентификатор_среды_исполения -p:PublishSingleFile=true путь/до/файла_проекта
```

- Обрезать неиспользуемые библиотеки чтобы уменьшить размер развёртывания приложения:

```bash
dotnet publish --self-contained true --runtime идентификатор_среды_исполения -p:PublishTrimmed=true путь/до/файла_проекта
```

- Скомпилировать проект .NET без восстановления зависимостей:

```bash
dotnet publish --no-restore путь/до/файла_проекта
```

- Указать целевую папку:

```bash
dotnet publish --output путь/до/папки путь/до/файла_проекта
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | dotnet-publish: add Russian translation (#4805) | 2020-10-24T14:53:00 | [3972f8ed94a9](https://github.com/tldr-pages/tldr/commit/3972f8ed94a9a401cd1d640ea3f91eee1d933ebb)

