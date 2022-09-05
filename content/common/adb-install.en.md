---
author: ['Hugh', 'Axel Navarro']
date: 1662316713
title: "adb install"
description: "adb install, Android Debug Bridge Install: Push packages to an Android emulator instance or connected Android devices."
categories: "common"
---
> More information: <https://developer.android.com/studio/command-line/adb>.

- Push an Android application to an emulator/device:

```bash
adb install path/to/file.apk
```

- Push an Android application to a specific emulator/device (overrides `$ANDROID_SERIAL`):

```bash
adb -s serial_number install path/to/file.apk
```

- Reinstall an existing app, keeping its data:

```bash
adb install -r path/to/file.apk
```

- Push an Android application allowing version code downgrade (debuggable packages only):

```bash
adb install -d path/to/file.apk
```

- Grant all permissions listed in the app manifest:

```bash
adb install -g path/to/file.apk
```

- Quickly update an installed package by only updating the parts of the APK that changed:

```bash
adb install --fastdeploy path/to/file.apk
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Hugh](mailto:52786639+HUGHNew@users.noreply.github.com) | adb-install: add -d example (#8423) | 2022-09-04T20:38:33 | [62b2ca653f79](https://github.com/tldr-pages/tldr/commit/62b2ca653f79efa6c22ed7b906c6dd2e79f69c0a)
[Axel Navarro](mailto:navarroaxel@gmail.com) | adb-install: add -s example (#8159) | 2022-06-28T04:26:43 | [b5bc4bbf18c2](https://github.com/tldr-pages/tldr/commit/b5bc4bbf18c27db96bcdb9e565c046d562b0d32e)
[Axel Navarro](mailto:navarroaxel@gmail.com) | emulator: add page (#4326) | 2020-09-14T13:58:51 | [928f80da0146](https://github.com/tldr-pages/tldr/commit/928f80da01467fdc4e1d73a589be277d54c50ccf)
[Axel Navarro](mailto:navarroaxel@gmail.com) | adb-install: add page (#4286) | 2020-08-28T15:18:03 | [1669465f5f36](https://github.com/tldr-pages/tldr/commit/1669465f5f36ff5e3a8854f4765c35943c6ba8c6)

