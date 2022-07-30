---
author: ['Managor']
date: 1637635730
title: "pw-loopback"
description: "pw-loopback, Tool for creating loopback devices in pipewire."
categories: "linux"
---
> More information: <https://gitlab.freedesktop.org/pipewire/pipewire/-/wikis/Virtual-Devices>.

- Create a loopback device with the default loopback behavior:

```bash
pw-loopback
```

- Create a loopback device that automatically connects to the speakers:

```bash
pw-loopback -m '[FL FR]' --capture-props='media.class=Audio/Sink'
```

- Create a loopback device that automatically connects to the microphone:

```bash
pw-loopback -m '[FL FR]' --playback-props='media.class=Audio/Source'
```

- Create a dummy loopback device that doesn't automatically connect to anything:

```bash
pw-loopback -m '[FL FR]' --capture-props='media.class=Audio/Sink' --playback-props='media.class=Audio/Source'
```

- Create a loopback device that automatically connects to the speakers and swaps the left and right channels between the sink and source:

```bash
pw-loopback --capture-props='media.class=Audio/Sink audio.position=[FL FR]' --playback-props='audio.position=[FR FL]'
```

- Create a loopback device that automatically connects to the microphone and swaps the left and right channels between the sink and source:

```bash
pw-loopback --capture-props='audio.position=[FR FL]' --playback-props='media.class=Audio/Source audio.position=[FL FR]'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Managor](mailto:42655600+Managor@users.noreply.github.com) | pw-loopback: refresh (#7304) | 2021-11-23T03:48:50 | [7a17f0cdcf9a](https://github.com/tldr-pages/tldr/commit/7a17f0cdcf9ade9a5362d07267dbdd88d169e400)
[Managor](mailto:42655600+Managor@users.noreply.github.com) | pw-loopback: add page (#6421) | 2021-09-05T16:44:42 | [05e131c71840](https://github.com/tldr-pages/tldr/commit/05e131c718403bbcecd45134e5db246d3ea680cf)

