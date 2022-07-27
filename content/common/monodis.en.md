---
author: ['Marco Bonelli', 'Starbeamrainbowlabs']
date: 1559564381
title: "monodis, TLDR Pages"
description: "monodis, The Mono Common Intermediate Language (CIL) disassembler."
categories: "common"
---
> More information: <https://www.mono-project.com/docs/tools+libraries/tools/monodis/>.

- Disassemble an assembly to textual CIL:

```bash
monodis path/to/assembly.exe
```

- Save the output to a file:

```bash
monodis --output=path/to/output.il path/to/assembly.exe
```

- Show information about an assembly:

```bash
monodis --assembly path/to/assembly.dll
```

- List the references of an assembly:

```bash
monodis --assemblyref path/to/assembly.exe
```

- List all the methods in an assembly:

```bash
monodis --method path/to/assembly.exe
```

- Show a list of resources embedded within an assembly:

```bash
monodis --manifest path/to/assembly.dll
```

- Extract all the embedded resources to the current directory:

```bash
monodis --mresources path/to/assembly.dll
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | monodis: add page (#2558) | 2018-11-07T07:15:38 | [8a2f2269877a](https://github.com/tldr-pages/tldr/commit/8a2f2269877adb8e6123cce1146be6bc978d20ba)

