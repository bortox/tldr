---
author: ['Hugh']
date: 1662066989
title: "adb-logcat"
description: "adb-logcat, Dump a log of system messages."
categories: "common"
---
> More information: <https://developer.android.com/studio/command-line/logcat>.

- Display system logs:

```bash
adb logcat
```

- Display lines that match a regular expression:

```bash
adb logcat -e regular_expression
```

- Display logs for a tag in a specific mode ([V]erbose, [D]ebug, [I]nfo, [W]arning, [E]rror, [F]atal, [S]ilent), filtering other tags:

```bash
adb logcat tag:mode *:S
```

- Display logs for React Native applications in [V]erbose mode [S]ilencing other tags:

```bash
adb logcat ReactNative:V ReactNativeJS:V *:S
```

- Display logs for all tags with priority level [W]arning and higher:

```bash
adb logcat *:W
```

- Color the log (usually use with filters):

```bash
adb logcat -v color
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Hugh](mailto:52786639+HUGHNew@users.noreply.github.com) | adb-logcat: add page (#8424) | 2022-09-01T23:16:29 | [a158032e7e04](https://github.com/tldr-pages/tldr/commit/a158032e7e041db4a9fa2d8105f08680c78c32e0)

