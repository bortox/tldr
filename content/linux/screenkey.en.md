---
author: ['ashishbinu']
date: 1621691135
title: "screenkey"
description: "screenkey, A screencast tool to display keys pressed."
categories: "linux"
---
> More information: <https://www.thregr.org/~wavexx/software/screenkey/>.

- Display keys which are currently being pressed on the screen:

```bash
screenkey
```

- Display keys and mouse buttons which are currently being pressed on the screen:

```bash
screenkey --mouse
```

- Launch the settings menu of screenkey:

```bash
screenkey --show-settings
```

- Launch screenkey at a specific position:

```bash
screenkey --position top|center|bottom|fixed
```

- Change the format of the key modifiers displayed on screen:

```bash
screenkey --mods-mode normal|emacs|mac|win|tux
```

- Change the appearance of screenkey:

```bash
screenkey --bg-color "#a1b2c3" --font Hack --font-color yellow --opacity 0.8
```

- Drag and select a window on screen to display screenkey:

```bash
screenkey --position fixed --geometry $(slop -n -f '%g')
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[ashishbinu](mailto:56691622+ashishbinu@users.noreply.github.com) | screenkey: add page (#5999) Co-authored-by: CleanMachine1 <78213164+CleanMachine1@users.noreply.github.com> Co-authored-by: bl-ue [...] | 2021-05-22T15:45:35 | [fe7a55124a9c](https://github.com/tldr-pages/tldr/commit/fe7a55124a9cc15e9a596cb4c201cdd6f332720a)

