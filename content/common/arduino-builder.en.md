---
author: ['bl-ue', 'marchersimon']
date: 1621541621
title: "arduino-builder"
description: "arduino-builder, A command-line tool for compiling arduino sketches."
categories: "common"
---
> DEPRECATION WARNING: This tool is being phased out in favor of `arduino`.

> More information: <https://github.com/arduino/arduino-builder>.

- Compile a sketch:

```bash
arduino-builder -compile path/to/sketch.ino
```

- Specify the debug level (1 to 10, defaults to 5):

```bash
arduino-builder -debug-level level
```

- Specify a custom build directory:

```bash
arduino-builder -build-path path/to/build_directory
```

- Use a build option file, instead of specifying `--hardware`, `--tools`, etc. manually every time:

```bash
arduino-builder -build-options-file path/to/build.options.json
```

- Enable verbose mode:

```bash
arduino-builder -verbose true
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | arduino-builder: add page (#5391) | 2021-03-13T21:57:48 | [e1bb083c5b65](https://github.com/tldr-pages/tldr/commit/e1bb083c5b659c4fb4c5b84d0dac5c49f7b910e4)

