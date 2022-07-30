---
author: ['marchersimon']
date: 1615671826
title: "arduino"
description: "arduino, Arduino Studio - Integrated Development Environment for the Arduino platform."
categories: "common"
---
> More information: <https://github.com/arduino/Arduino/blob/master/build/shared/manpage.adoc>.

- Build a sketch:

```bash
arduino --verify path/to/file.ino
```

- Build and upload a sketch:

```bash
arduino --upload path/to/file.ino
```

- Build and upload a sketch to an Arduino Nano with an Atmega328p CPU, connected on port `/dev/ttyACM0`:

```bash
arduino --board arduino:avr:nano:cpu=atmega328p --port /dev/ttyACM0 --upload path/to/file.ino
```

- Set the preference `name` to a given `value`:

```bash
arduino --pref name=value
```

- Build a sketch, put the build results in the build directory, and reuse any previous build results in that directory:

```bash
arduino --pref build.path=path/to/build_directory --verify path/to/file.ino
```

- Save any (changed) preferences to `preferences.txt`:

```bash
arduino --save-prefs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | arduino: add page (#5389) | 2021-03-13T22:43:46 | [8c8445aca425](https://github.com/tldr-pages/tldr/commit/8c8445aca425c6a9ab21ece6c85deb45769e7d3c)

