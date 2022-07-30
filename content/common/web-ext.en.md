---
author: ['Axel Navarro', 'Owen Voke', 'bl-ue', 'Marco Bonelli']
date: 1643827401
title: "web-ext"
description: "web-ext, A command-line tool for managing web extension development."
categories: "common"
---
> More information: <https://github.com/mozilla/web-ext>.

- Run the web extension in the current directory in Firefox:

```bash
web-ext run
```

- Run a web extension from a specific directory in Firefox:

```bash
web-ext run --source-dir path/to/directory
```

- Display verbose execution output:

```bash
web-ext run --verbose
```

- Run a web extension in Firefox Android:

```bash
web-ext run --target firefox-android
```

- Lint the manifest and source files for errors:

```bash
web-ext lint
```

- Build and package the extension:

```bash
web-ext build
```

- Display verbose build output:

```bash
web-ext build --verbose
```

- Sign a package for self-hosting:

```bash
web-ext sign --api-key api_key --api-secret api_secret
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | *: use author link instead of npm package (#7730) | 2022-02-02T19:43:21 | [c2c16f61acbd](https://github.com/tldr-pages/tldr/commit/c2c16f61acbdca1933961fbbc20a80bdae76ece5)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | web-ext: add page (#2739) | 2019-02-01T17:57:45 | [5b53cf8b283f](https://github.com/tldr-pages/tldr/commit/5b53cf8b283fe19b220b7389de5262364b6e769c)

