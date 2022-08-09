---
author: ['CleanMachine1']
date: 1659964342
title: "gum"
description: "gum, A tool for making glamorous shell scripts."
categories: "common"
---
> More information: <https://github.com/charmbracelet/gum>.

- Interactively pick a specific option to print to `stdout`:

```bash
gum choose "option_1" "option_2" "option_3"
```

- Open an interactive prompt for the user to input a string with a specific placeholder:

```bash
gum input --placeholder "value"
```

- Open an interactive confirmation prompt and exit with either `0` or `1`:

```bash
gum confirm "Continue?" --default=false --affirmative "Yes" --negative "No" && echo "Yes selected" || echo "No selected"
```

- Show a spinner while a command is taking place with text alongside:

```bash
gum spin --spinner dot|line|minidot|jump|pulse|points|globe|moon|monkey|meter|hamburger --title "loading..." -- command
```

- Format text to include emojis:

```bash
gum format -t emoji ":smile: :heart: hello"
```

- Interactively prompt for multi-line text (CTRL + D to save) and write to `data.txt`:

```bash
gum write > data.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | gum: add page (#8314) | 2022-08-08T15:12:22 | [0b148c3071f1](https://github.com/tldr-pages/tldr/commit/0b148c3071f1545a8746de8f9fec2cd638304ffb)

