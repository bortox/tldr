---
author: ['Axel Navarro']
date: 1632334545
title: "starship"
description: "starship, The minimal, blazing-fast, and infinitely customizable prompt for any shell."
categories: "common"
---
> Some subcommands such as `starship init` have their own usage documentation.

> More information: <https://starship.rs>.

- Print the starship integration code for the specified shell:

```bash
starship init bash|elvish|fish|ion|powershell|tcsh|zsh
```

- Explain each part of the current prompt and show the time taken to render them:

```bash
starship explain
```

- Print the computed starship configuration (use `--default` to print default configuration instead):

```bash
starship print-config
```

- List supported modules:

```bash
starship module --list
```

- Edit the starship configuration in the default editor:

```bash
starship configure
```

- Create a bug report GitHub issue pre-populated with information about the system and starship configuration:

```bash
starship bug-report
```

- Print the completion script for the specified shell:

```bash
starship completions bash|elvish|fish|powershell|zsh
```

- Display help for a subcommand:

```bash
starship subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | starship: mention subcommand page (#6583) * Update starship.md * starship-init: fix typo | 2021-09-22T20:15:45 | [778a7a14c3d1](https://github.com/tldr-pages/tldr/commit/778a7a14c3d186801e38171de4898ba6f161f75d)
[Axel Navarro](mailto:navarroaxel@gmail.com) | starship: add page (#5901) | 2021-05-14T03:28:00 | [5d6be64c8006](https://github.com/tldr-pages/tldr/commit/5d6be64c8006594f0240c568e34e6019158a463e)

