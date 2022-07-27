---
author: ['Managor']
date: 1632829999
title: "pw-play, TLDR Pages"
description: "pw-play, Shorthand tool for pw-cat --playback."
categories: "linux"
---
> More information: <https://fedoraproject.org/wiki/QA:Testcase_PipeWire_PipeWire_CLI>.

- List all available playback targets:

```bash
pw-play --list-targets
```

- Play a wav sound file over the default target:

```bash
pw-play path/to/file.wav
```

- Play a wav sound file at a different volume level:

```bash
pw-play --volume=0.1 path/to/file.wav
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Managor](mailto:42655600+Managor@users.noreply.github.com) | pw-cat, pw-play, pw-record: add page (#6602) | 2021-09-28T13:53:19 | [682544fc1ac6](https://github.com/tldr-pages/tldr/commit/682544fc1ac6ff9eb849510c4369831434437482)

