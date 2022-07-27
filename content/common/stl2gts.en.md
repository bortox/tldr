---
author: ['marchersimon']
date: 1621588390
title: "stl2gts, TLDR Pages"
description: "stl2gts, Convert STL files into the GTS (GNU triangulated surface library) file format."
categories: "common"
---
> More information: <https://manned.org/stl2gts>.

- Convert an STL file to a GTS file:

```bash
stl2gts < path/to/file.stl > path/to/file.gts
```

- Convert an STL file to a GTS file and revert face normals:

```bash
stl2gts --revert < path/to/file.stl > path/to/file.gts
```

- Convert an STL file to a GTS file and do not merge vertices:

```bash
stl2gts --nomerge < path/to/file.stl > path/to/file.gts
```

- Convert an STL file to a GTS file and display surface statistics:

```bash
stl2gts --verbose < path/to/file.stl > path/to/file.gts
```

- Print help for `stl2gts`:

```bash
stl2gts --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | stl2gts: add page (#5969) | 2021-05-21T11:13:10 | [a96dddd22432](https://github.com/tldr-pages/tldr/commit/a96dddd2243250bf6ea89fe4ddb85b4044df496c)

