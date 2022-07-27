---
author: ['Axel Navarro']
date: 1615375170
title: "qdbus, TLDR Pages"
description: "qdbus, Inter-Process Communication (IPC) and Remote Procedure Calling (RPC) mechanism originally developed for Linux."
categories: "common"
---
> More information: <https://doc.qt.io/qt-5/qtdbus-index.html>.

- List available service names:

```bash
qdbus
```

- List object paths for a specific service:

```bash
qdbus service_name
```

- List methods, signals and properties available on a specific object:

```bash
qdbus service_name /path/to/object
```

- Execute a specific method passing arguments and display the returned value:

```bash
qdbus service_name /path/to/object method_name argument1 argument2
```

- Display the current brightness value in a KDE Plasma session:

```bash
qdbus org.kde.Solid.PowerManagement /org/kde/Solid/PowerManagement/Actions/BrightnessControl org.kde.Solid.PowerManagement.Actions.BrightnessControl.brightness
```

- Set a specific brightness to a KDE Plasma session:

```bash
qdbus org.kde.Solid.PowerManagement /org/kde/Solid/PowerManagement/Actions/BrightnessControl org.kde.Solid.PowerManagement.Actions.BrightnessControl.setBrightness 5000
```

- Invoke volume up shortcut in a KDE Plasma session:

```bash
qdbus org.kde.kglobalaccel /component/kmix invokeShortcut "increase_volume"
```

- Display help:

```bash
qdbus --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | qdbus: add page (#5360) | 2021-03-10T12:19:30 | [1722117f90c7](https://github.com/tldr-pages/tldr/commit/1722117f90c7be84a91df4d8d2ce3f36f516a381)

