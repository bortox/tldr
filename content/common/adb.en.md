---
author: ['Waldir Pimenta', 'Agniva De Sarker', 'Schneider', 'Eric Rösch', 'lagel', 'Marco Bonelli', 'Ruben Vereecken', 'marchersimon']
date: 1631521281
title: "adb"
description: "adb, Android Debug Bridge: communicate with an Android emulator instance or connected Android devices."
categories: "common"
---
> Some subcommands such as `adb shell` have their own usage documentation.

> More information: <https://developer.android.com/studio/command-line/adb>.

- Check whether the adb server process is running and start it:

```bash
adb start-server
```

- Terminate the adb server process:

```bash
adb kill-server
```

- Start a remote shell in the target emulator/device instance:

```bash
adb shell
```

- Push an Android application to an emulator/device:

```bash
adb install -r path/to/file.apk
```

- Copy a file/directory from the target device:

```bash
adb pull path/to/device_file_or_directory path/to/local_destination_directory
```

- Copy a file/directory to the target device:

```bash
adb push path/to/local_file_or_directory path/to/device_destination_directory
```

- Get a list of connected devices:

```bash
adb devices
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | adb.md add homepage | 2019-04-11T09:49:15 | [a24c695c7a6c](https://github.com/tldr-pages/tldr/commit/a24c695c7a6c8cb26ca2cc8eb3a6929f5e53b6ef)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Eric Rösch](mailto:eric.roesch@web.de) | adb: add push, pull and devices commands (#1166) | 2016-11-26T17:03:36 | [1928329a6593](https://github.com/tldr-pages/tldr/commit/1928329a6593ae236f2db88f4703bc7b255927d6)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | use command name as main header, per guidelines | 2016-09-07T21:30:46 | [64a30e82ca3f](https://github.com/tldr-pages/tldr/commit/64a30e82ca3f909360d11a87e36900bf3ae84610)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Apply the 'path/to/item' convention uniformly (#947) | 2016-07-13T10:53:22 | [fa8b2d8f92ab](https://github.com/tldr-pages/tldr/commit/fa8b2d8f92abfcbea46036b8a30c129ac53abdcb)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lagel](mailto:lagel@live.com) | Add adb commands | 2016-01-06T14:57:19 | [5bbc71e9cf0d](https://github.com/tldr-pages/tldr/commit/5bbc71e9cf0d8786e0d47050d06322eb559f45f3)

