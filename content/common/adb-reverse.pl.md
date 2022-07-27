---
author: ['Krzysztof Bociurko']
date: 1604236574
title: "adb reverse, TLDR Pages"
description: "adb reverse, Android Debug Bridge Reverse: zwrotne połączenie socketowe z emulowanego lub prawdziwego urządzenia Android."
categories: "common"
---
> Więcej informacji: <https://developer.android.com/studio/command-line/adb>.

- Listuj wszystkie zwrotne połączenia socketowe z emulatorów i urządzeń:

```bash
adb reverse --list
```

- Przekieruj port TCP z emulatora lub urządzenia do localhost:

```bash
adb reverse tcp:remote_port tcp:local_port
```

- Usuń wybrane zwrotne połączenie z emulatora lub urządzenia:

```bash
adb reverse --remove tcp:remote_port
```

- Usuń wszystkie zwrotne połączenie z emulatorów lub urządzeń:

```bash
adb reverse --remove-all
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | adb, adb-reverse: add polish translation (#4901) | 2020-11-01T14:16:14 | [396dfa0ce1e0](https://github.com/tldr-pages/tldr/commit/396dfa0ce1e0d965cdf90f7458baaa6b5211f900)

