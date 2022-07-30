---
author: ['bl-ue', 'Ryzhehvost']
date: 1610462196
title: "AdGuardHome"
description: "AdGuardHome, Программное обеспечение для блокировки рекламы и отслеживания во всей сети."
categories: "common"
---
> Больше информации: <https://github.com/AdguardTeam/AdGuardHome>.

- Запустить AdGuard Home:

```bash
AdGuardHome
```

- Запустить AdGuard с заданной конфигурацией:

```bash
AdGuardHome --config путь/до/AdGuardHome.yaml
```

- Установить рабочую папку, где будут сохранятья данные:

```bash
AdGuardHome --work-dir путь/до/папки
```

- Установить или удалить AdGuard Home как службу:

```bash
AdGuardHome --service install|uninstall
```

- Запустить службу AdGuard Home:

```bash
AdGuardHome --service start
```

- Перезагрузить конфигурацию для службы AdGuard Home:

```bash
AdGuardHome --service reload
```

- Остановить или перезапустить службу AdGuard Home:

```bash
AdGuardHome --service stop|restart
```
Список изменений, внесенных в эту документацию


Автор | Описание | Формат даты ISO 8601 | Ссылка на GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Ryzhehvost](mailto:kotlyar.andrey@gmail.com) | aapt to ag: add Russian translation (#4882) | 2020-11-16T19:18:22 | [c2420e8db02a](https://github.com/tldr-pages/tldr/commit/c2420e8db02a6c24eb77d06c2b6394b8b6936421)

