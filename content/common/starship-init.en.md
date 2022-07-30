---
author: ['Axel Navarro']
date: 1632334545
title: "starship init"
description: "starship init, Print shell integration code for starship."
categories: "common"
---
> More information: <https://starship.rs>.

- Display the subcommand help:

```bash
starship init --help
```

- Print the starship integration code for the specified shell:

```bash
starship init bash|elvish|fish|ion|powershell|tcsh|zsh
```

- Append the `starship` integration code to `~/.bashrc`:

```bash
starship init bash >> ~/.bashrc
```

- Append the `starship` integration code to `~/.zshrc`:

```bash
starship init zsh >> ~/.zshrc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | starship: mention subcommand page (#6583) * Update starship.md * starship-init: fix typo | 2021-09-22T20:15:45 | [778a7a14c3d1](https://github.com/tldr-pages/tldr/commit/778a7a14c3d186801e38171de4898ba6f161f75d)
[Axel Navarro](mailto:navarroaxel@gmail.com) | starship-init: add page (#5972) | 2021-05-18T20:09:17 | [6b40df8c17b7](https://github.com/tldr-pages/tldr/commit/6b40df8c17b77fe6c005fb217426f710411c8f1b)

