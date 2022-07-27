---
author: ['Marco Bonelli', 'Schneider', 'Waldir Pimenta']
date: 1559564381
title: "assimp, TLDR Pages"
description: "assimp, Command-line client for the Open Asset Import Library."
categories: "common"
---
> Supports loading of 40+ 3D file formats, and exporting to several popular 3D formats.

> More information: <http://www.assimp.org/>.

- List all supported import formats:

```bash
assimp listext
```

- List all supported export formats:

```bash
assimp listexport
```

- Convert a file to one of the supported output formats, using the default parameters:

```bash
assimp export input_file.stl output_file.obj
```

- Convert a file using custom parameters (the dox_cmd.h file in assimp's source code lists available parameters):

```bash
assimp export input_file.stl output_file.obj parameters
```

- Display a summary of a 3D file's contents:

```bash
assimp info path/to/file
```

- List all supported subcommands ("verbs"):

```bash
assimp help
```

- Get help on a specific subcommand (e.g. the parameters specific to it):

```bash
assimp subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | assimp.md: add homepage | 2019-04-12T14:41:22 | [8adc5507edb5](https://github.com/tldr-pages/tldr/commit/8adc5507edb5f376aaec31e41cea76f4e587048a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | assimp: add page (#1028) | 2016-10-31T08:51:40 | [dc085927c6c7](https://github.com/tldr-pages/tldr/commit/dc085927c6c7cb03968c6ba70e70b4ad84096aad)

