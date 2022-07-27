---
author: ['Axel Navarro', 'Gustavo Dias Alexandre']
date: 1599213434
title: "adb shell, TLDR Pages"
description: "adb shell, Android Debug Bridge Shell: Run remote shell commands on an Android emulator instance or connected Android devices."
categories: "common"
---
> More information: <https://developer.android.com/studio/command-line/adb>.

- Start a remote interactive shell on the emulator/device:

```bash
adb shell
```

- Get all the properties from emulator or device:

```bash
adb shell getprop
```

- Revert all runtime permissions to their default:

```bash
adb shell pm reset-permissions
```

- Revoke a dangerous permission for an application:

```bash
adb shell pm revoke package permission
```

- Trigger a key event:

```bash
adb shell input keyevent keycode
```

- Clear the data of an application on an emulator or device:

```bash
adb shell pm clear package
```

- Start an activity on emulator/device:

```bash
adb shell am start -n package/activity
```

- Start the home activity on an emulator or device:

```bash
adb shell am start -W -c android.intent.category.HOME -a android.intent.action.MAIN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gustavo Dias Alexandre](mailto:gfdiasa@gmail.com) | adb-shell: add getprop example (#4311) | 2020-09-04T11:57:14 | [54e7a34498ce](https://github.com/tldr-pages/tldr/commit/54e7a34498cef383ea6d6881717cd2230839629e)
[Axel Navarro](mailto:navarroaxel@gmail.com) | adb-shell: add page (#4287) | 2020-08-31T01:20:36 | [d103a229a7e6](https://github.com/tldr-pages/tldr/commit/d103a229a7e669fe554f7449373dd7975f4989fb)

