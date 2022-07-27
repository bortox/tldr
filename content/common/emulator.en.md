---
author: ['Axel Navarro', 'bl-ue']
date: 1621541621
title: "emulator, TLDR Pages"
description: "emulator, Manager Android emulators from the command-line."
categories: "common"
---
> More information: <https://developer.android.com/studio/run/emulator-commandline>.

- Display the help:

```bash
emulator -help
```

- Start an Android emulator device:

```bash
emulator -avd name
```

- Display the webcams on your development computer that are available for emulation:

```bash
emulator -avd name -webcam-list
```

- Start an emulator overriding the facing back camera setting (use `-camera-front` for front camera):

```bash
emulator -avd name -camera-back none|emulated|webcamN
```

- Start an emulator, with a maximum network speed:

```bash
emulator -avd name -netspeed gsm|hscsd|gprs|edge|hsdpa|lte|evdo|full
```

- Start an emulator with network latency:

```bash
emulator -avd name -netdelay gsm|hscsd|gprs|edge|hsdpa|lte|evdo|none
```

- Start an emulator, making all TCP connections through a specified HTTP/HTTPS proxy (port number is required):

```bash
emulator -avd name -http-proxy http://example.com:80
```

- Start an emulator with a given SD card partition image file:

```bash
emulator -avd name -sdcard path/to/sdcard.img
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Axel Navarro](mailto:navarroaxel@gmail.com) | emulator: add page (#4326) | 2020-09-14T13:58:51 | [928f80da0146](https://github.com/tldr-pages/tldr/commit/928f80da01467fdc4e1d73a589be277d54c50ccf)

