---
author: ['Stig124', 'Jack Featherstone', 'Guido Lena Cota', 'git-em']
date: 1646800268
title: "dunstify, TLDR Pages"
description: "dunstify, A notification tool that is an extension of notify-send, but has more features based around dunst."
categories: "linux"
---
> Works with all options that work for notify-send.

> More information: <https://github.com/dunst-project/dunst/wiki/Guides>.

- Show a notification with a given title and message:

```bash
dunstify "Title" "Message"
```

- Show a notification with specified urgency:

```bash
dunstify "Title" "Message" -u low|normal|critical
```

- Specify a message ID (overwrites any previous messages with the same ID):

```bash
dunstify "Title" "Message" -r 123
```

- To see other possible options:

```bash
notify-send --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | linux/*: replace man.archlinux.com link (#7861) * linux/*: replace man.archlinux.com Does not replace links of pages directly [...] | 2022-03-09T05:31:08 | [8628cba2ebf0](https://github.com/tldr-pages/tldr/commit/8628cba2ebf0939f9aec27530c42351215334eeb)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Jack Featherstone](mailto:jfeatherstone123@gmail.com) | dunstify: add page (#3501) * dunstify: add page * dunstify: add page * fixed some formatting and wording issues, added notify-send [...] | 2019-10-31T02:30:22 | [974cafbef5f0](https://github.com/tldr-pages/tldr/commit/974cafbef5f0d3377a7a082251b135dc942ca543)

