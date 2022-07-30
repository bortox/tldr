---
author: ['Hugo Locurcio', 'Schneider', 'Marco Bonelli']
date: 1583685775
title: "godot"
description: "godot, An open source 2D and 3D game engine."
categories: "common"
---
> More information: <https://godotengine.org/>.

- Run a project if the current directory contains a `project.godot` file, otherwise open the project manager:

```bash
godot
```

- Edit a project (the current directory must contain a `project.godot` file):

```bash
godot -e
```

- Open the project manager even if the current directory contains a `project.godot` file:

```bash
godot -p
```

- Export a project for a given export preset (the preset must be defined in the project):

```bash
godot --export preset output_path
```

- Execute a standalone GDScript file (the script must inherit from `SceneTree` or `MainLoop`):

```bash
godot -s script.gd
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Hugo Locurcio](mailto:hugo.locurcio@hugo.pro) | godot: update the `--export` example (#3895) This also adds more information about the `-s` switch's requirements. | 2020-03-08T17:42:55 | [236ba09423e5](https://github.com/tldr-pages/tldr/commit/236ba09423e5fb494ba82a15f362dcade5d82502)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | godot.md add homepage | 2019-04-11T09:49:15 | [7621241a2bba](https://github.com/tldr-pages/tldr/commit/7621241a2bba876cc82d7344315b661336866c45)
[Hugo Locurcio](mailto:hugo.locurcio@hugo.pro) | godot: add page (#2183) | 2018-07-12T19:48:27 | [bf5491b2eebe](https://github.com/tldr-pages/tldr/commit/bf5491b2eebee4e37f24cf090bbaa720285d3bfb)

