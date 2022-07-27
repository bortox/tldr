---
author: ['Emily Grace Seville', 'Ruben Vereecken', 'Zlatan Vasović', 'liv', 'Guido Lena Cota', 'Rakesh Das']
date: 1647882468
title: "notify-send, TLDR Pages"
description: "notify-send, Uses the current desktop environment's notification system to create a notification."
categories: "linux"
---
> More information: <https://manned.org/notify-send>.

- Show a notification with the title "Test" and the content "This is a test":

```bash
notify-send "Test" "This is a test"
```

- Show a notification with a custom icon:

```bash
notify-send -i icon.png "Test" "This is a test"
```

- Show a notification for 5 seconds:

```bash
notify-send -t 5000 "Test" "This is a test"
```

- Show a notification with an app's icon and name:

```bash
notify-send "Test" --icon=google-chrome --app-name="Google Chrome"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[liv](mailto:sokolov.dominika@gmail.com) | notify-send: Add `--app-name` to example (#7384) | 2021-11-07T18:25:35 | [81a0b019c922](https://github.com/tldr-pages/tldr/commit/81a0b019c922f83ae1a3a67d11e48880a1c4b1a2)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | notify-send: add an icon example (#4056) | 2020-05-21T01:13:29 | [924be075aabf](https://github.com/tldr-pages/tldr/commit/924be075aabf51066b58d661ea2f8f5a235ec75d)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reworked notify-send to my liking | 2016-01-29T14:28:47 | [0ed875b81723](https://github.com/tldr-pages/tldr/commit/0ed875b817231ff4c7c0c5ef124fc2e62c990b4d)
[Rakesh Das](mailto:rakeshdaskowshik@gmail.com) | Added notify-send | 2016-01-29T14:28:29 | [5b6a4c8bf95c](https://github.com/tldr-pages/tldr/commit/5b6a4c8bf95c4f88290321c3db12b2cf744dd978)
[Rakesh Das](mailto:rakeshdaskowshik@gmail.com) | Added notify-send | 2016-01-29T14:28:29 | [054f36d47575](https://github.com/tldr-pages/tldr/commit/054f36d47575933cecfe166244086bdf2931b5fa)
[Rakesh Das](mailto:rakeshdaskowshik@gmail.com) | Added notify-send | 2016-01-29T14:28:29 | [cb1550792189](https://github.com/tldr-pages/tldr/commit/cb1550792189a86d08a7b764c710ab47451554c4)

