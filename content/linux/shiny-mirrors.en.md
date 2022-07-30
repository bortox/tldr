---
author: ['Arisa Snowbell']
date: 1636365558
title: "shiny-mirrors"
description: "shiny-mirrors, Generate a pacman mirror list for Manjaro Linux."
categories: "linux"
---
> Every run of shiny-mirrors requires you to synchronize your database and update your system using `sudo pacman -Syyu`.

> More information: <https://gitlab.com/Arisa_Snowbell/shiny-mirrors/-/blob/domina/shiny-mirrors/man/shiny-mirrors.md>.

- Get the status of the current mirrors:

```bash
shiny-mirrors status
```

- Generate a mirror list using the default behavior:

```bash
sudo shiny-mirrors refresh
```

- Display the current configuration file:

```bash
shiny-mirrors config show
```

- Switch to a different branch interactively:

```bash
sudo shiny-mirrors config --branch
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Arisa Snowbell](mailto:arisa.snowbell@gmail.com) | shiny-mirrors: add page (#7393) | 2021-11-08T10:59:18 | [b25dda6d9887](https://github.com/tldr-pages/tldr/commit/b25dda6d98877d14327f9403e0f59275b5855194)

