---
author: ['Managor']
date: 1632829999
title: "pw-cat"
description: "pw-cat, Pipewire tool for playing and recording audio files."
categories: "linux"
---
> More information: <https://fedoraproject.org/wiki/QA:Testcase_PipeWire_PipeWire_CLI>.

- List all available playback targets:

```bash
pw-cat --playback --list-targets
```

- Play a WAV file over the default target:

```bash
pw-cat --playback path/to/file.wav
```

- List all available record targets:

```bash
pw-cat --record --list-targets
```

- Record a sample recording at a different volume level:

```bash
pw-cat --record --volume=0.1 path/to/file.wav
```

- Record a sample recording using a different sample rate:

```bash
pw-cat --record --rate=6000 path/to/file.wav
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Managor](mailto:42655600+Managor@users.noreply.github.com) | pw-cat, pw-play, pw-record: add page (#6602) | 2021-09-28T13:53:19 | [682544fc1ac6](https://github.com/tldr-pages/tldr/commit/682544fc1ac6ff9eb849510c4369831434437482)

