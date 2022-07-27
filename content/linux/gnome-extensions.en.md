---
author: ['Bhaskar', 'Seth']
date: 1619871588
title: "gnome-extensions, TLDR Pages"
description: "gnome-extensions, Manage gnome extensions from the terminal."
categories: "linux"
---
> More information: <https://wiki.gnome.org/Projects/GnomeShell/Extensions>.

- Display the version:

```bash
gnome-extensions version
```

- List all the installed extensions:

```bash
gnome-extensions list
```

- Display information about a specific extension:

```bash
gnome-extensions info "extension_id"
```

- Display help for a subcommand (like `list`):

```bash
gnome-extensions help subcommand
```

- Enable a specific extension:

```bash
gnome-extensions enable "extension_id"
```

- Disable a specific extension:

```bash
gnome-extension disable "extension_id"
```

- Uninstall a specific extension:

```bash
gnome-extension uninstall "extension_id"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth](mailto:seth@elypia.org) | gnome-extensions: fix typo (#5864) | 2021-05-01T14:19:48 | [50d6e5906a4b](https://github.com/tldr-pages/tldr/commit/50d6e5906a4b27fff00edfd617ca0c3e81551c5f)
[Bhaskar](mailto:43211224+BhaskarDutta2209@users.noreply.github.com) | gnome-extensions: add page (#4652) | 2020-10-12T15:04:25 | [c5f2b57ef17a](https://github.com/tldr-pages/tldr/commit/c5f2b57ef17a1dd786c5ff0dd3978d8842d2f257)

