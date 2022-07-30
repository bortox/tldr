---
author: ['bl-ue', 'six', 'Seth Falco', 'Muhammad Falak R Wani']
date: 1643809606
title: "meson"
description: "meson, SCons-like build system that uses python as a front-end language and Ninja as a building backend."
categories: "common"
---
> More information: <https://mesonbuild.com>.

- Generate a C project with a given name and version:

```bash
meson init --language=c --name=myproject --version=0.1
```

- Configure the `builddir` with default values:

```bash
meson setup build_dir
```

- Build the project:

```bash
meson compile -C path/to/build_dir
```

- Run all tests in the project:

```bash
meson test
```

- Show the help:

```bash
meson --help
```

- Show version info:

```bash
meson --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | meson: add an example to run all tests in the project (#7740) Signed-off-by: Muhammad Falak R Wani <falakreyaz@gmail.com> | 2022-02-02T14:46:46 | [7b0f1fcd45c9](https://github.com/tldr-pages/tldr/commit/7b0f1fcd45c94f8f12e94aca7a3a3d3006922f01)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[six](mailto:354651432@qq.com) | meson: add page (#4281) | 2020-09-05T01:05:18 | [de8bb3bcd913](https://github.com/tldr-pages/tldr/commit/de8bb3bcd9137be5f8311981ecc08d5cabe3e9d5)

