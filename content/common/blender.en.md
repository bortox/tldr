---
author: ['Waldir Pimenta', 'Emily Grace Seville', 'Schneider', 'Marco Bonelli', 'marchersimon']
date: 1642351651
title: "blender"
description: "blender, Command-line interface to the Blender 3D computer graphics application."
categories: "common"
---
> Arguments are executed in the order they are given.

> More information: <https://manned.org/blender>.

- Render all frames of an animation in the background, without loading the UI (output is saved to `/tmp`):

```bash
blender --background filename.blend --render-anim
```

- Render an animation using a specific image naming pattern, in a path relative (`//`) to the .blend file:

```bash
blender --background filename.blend --render-output //render/frame_###.png --render-anim
```

- Render the 10th frame of an animation as a single image, saved to an existing directory (absolute path):

```bash
blender --background filename.blend --render-output /path/to/output_directory --render-frame 10
```

- Render the second last frame in an animation as a JPEG image, saved to an existing directory (relative path):

```bash
blender --background filename.blend --render-output //output_directory --render-frame JPEG --render-frame -2
```

- Render the animation of a specific scene, starting at frame 10 and ending at frame 500:

```bash
blender --background filename.blend --scene scene_name --frame-start 10 -e 500 --render-anim
```

- Render an animation at a specific resolution, by passing a Python expression:

```bash
blender --background filename.blend --python-expr 'import bpy; bpy.data.scenes[0].render.resolution_percentage = 25' --render-anim
```

- Start an interactive Blender session in the terminal with a python console (do `import bpy` after starting):

```bash
blender --background --python-console
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | blender: use long arguments (#7663) | 2022-01-16T17:47:31 | [41394e7515c9](https://github.com/tldr-pages/tldr/commit/41394e7515c966ebc13e3541500528c82fa9050e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | blender.md add homepage | 2019-04-11T09:49:15 | [e54a4b7859c3](https://github.com/tldr-pages/tldr/commit/e54a4b7859c31a957252e9fc089b0028df9ed21f)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | blender: add page (#1131) Mostly based on https://www.blender.org/manual/advanced/command_line/arguments.html with some additional [...] | 2016-11-26T16:55:38 | [b9fded2e1646](https://github.com/tldr-pages/tldr/commit/b9fded2e16464aa8f42ef0180300cb16698774cb)

