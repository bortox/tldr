---
author: ['Guido Lena Cota', 'Lucas Gabriel Schneider', 'Seth Falco', 'Owen Voke']
date: 1629050349
title: "eventcreate, TLDR Pages"
description: "eventcreate, Create custom entries in the event log."
categories: "windows"
---
> Event IDs can be any number between 1 and 1000.

> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/eventcreate>.

- Create a new event with a given ID (1-1000) in the log:

```bash
eventcreate /t success|error|warning|information /id id /d "message"
```

- Create an event in a specific event log:

```bash
eventcreate /l log_name /t type /id id /d "message"
```

- Create an event with a specific source:

```bash
eventcreate /so source_name /t type /id id /d "message"
```

- Create an event in a remote machine's event log:

```bash
eventcreate /s hostname /u username /p password /t type /id id /d "message"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | eventcreate: add page (#2376) | 2018-10-05T15:12:10 | [26088043305b](https://github.com/tldr-pages/tldr/commit/26088043305bcb4a888c3799c9e719b28240555f)

