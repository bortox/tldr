---
author: ['Owen Voke', 'pxgamer', 'Marco Bonelli']
date: 1559564381
title: "choco source"
description: "choco source, Manage sources for packages with Chocolatey."
categories: "windows"
---
> More information: <https://chocolatey.org/docs/commands-source>.

- List currently available sources:

```bash
choco source list
```

- Add a new package source:

```bash
choco source add --name name --source url
```

- Add a new package source with credentials:

```bash
choco source add --name name --source url --user username --password password
```

- Add a new package source with a client certificate:

```bash
choco source add --name name --source url --cert path/to/certificate
```

- Enable a package source:

```bash
choco source enable --name name
```

- Disable a package source:

```bash
choco source disable --name name
```

- Remove a package source:

```bash
choco source remove --name name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | choco-source: add link to homepage | 2019-03-20T06:53:44 | [aa8ab6cc42f8](https://github.com/tldr-pages/tldr/commit/aa8ab6cc42f89623e5f0d1c93613d847efd92074)
[Owen Voke](mailto:owzie123@gmail.com) | choco-source: add page (#2048) | 2018-03-29T18:03:56 | [8f238ae1dffa](https://github.com/tldr-pages/tldr/commit/8f238ae1dffa374cf0d5b9a22408aaf99cd40d71)

