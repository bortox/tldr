---
author: ['Anton Karmanov', 'Waldir Pimenta', 'Schneider', 'PFCKrutonium', 'Flex Zhong', 'Chasarr', 'Marco Bonelli']
date: 1612108259
title: "cmake"
description: "cmake, Cross-platform build automation system, that generates recipes for native build systems."
categories: "common"
---
> More information: <https://cmake.org/cmake/help/latest/manual/cmake.1.html>.

- Generate a build recipe in the current directory with `CMakeLists.txt` from a project directory:

```bash
cmake path/to/project_directory
```

- Generate a build recipe, with build type set to `Release` with CMake variable:

```bash
cmake path/to/project_directory -D CMAKE_BUILD_TYPE=Release
```

- Use a generated recipe in a given directory to build artifacts:

```bash
cmake --build path/to/build_directory
```

- Install the build artifacts into `/usr/local/` and strip debugging symbols:

```bash
cmake --install path/to/build_directory --strip
```

- Install the build artifacts using the custom prefix for paths:

```bash
cmake --install path/to/build_directory --strip --prefix path/to/directory
```

- Run a custom build target:

```bash
cmake --build path/to/build_directory --target target_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anton Karmanov](mailto:a.karmanov@inventati.org) | cmake: improve an example description Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2021-01-31T16:50:59 | [826e7c8e3c80](https://github.com/tldr-pages/tldr/commit/826e7c8e3c802aacb8b506ef098ae855cdcf3a04)
[Anton Karmanov](mailto:a.karmanov@inventati.org) | cmake: apply few review suggestions Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-01-31T16:50:59 | [da1db4d6464d](https://github.com/tldr-pages/tldr/commit/da1db4d6464d82adb8e44e15573663237a800167)
[Anton Karmanov](mailto:a.karmanov@inventati.org) | cmake: resolve PR conversations | 2021-01-31T16:50:59 | [32e858f5f7cf](https://github.com/tldr-pages/tldr/commit/32e858f5f7cfaee75c21bd22ddf8da934f766360)
[Anton Karmanov](mailto:a.karmanov@inventati.org) | cmake: apply suggestions from review Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-01-31T16:50:59 | [c39095a21da3](https://github.com/tldr-pages/tldr/commit/c39095a21da3d1ac458200d426d993975e10c944)
[Anton Karmanov](mailto:a.karmanov@inventati.org) | cmake: update --install example | 2021-01-31T16:50:59 | [64d4a41efbda](https://github.com/tldr-pages/tldr/commit/64d4a41efbda340e000b0ac69ad1c88b46e94f57)
[Anton Karmanov](mailto:a.karmanov@inventati.org) | cmake: fix linter issues | 2021-01-31T16:50:59 | [36d3ce201119](https://github.com/tldr-pages/tldr/commit/36d3ce201119e87f83da2c2288f6dcea0414147c)
[Anton Karmanov](mailto:a.karmanov@inventati.org) | cmake: update page Actualise examples and improve description. | 2021-01-31T16:50:59 | [bb6d3e72d839](https://github.com/tldr-pages/tldr/commit/bb6d3e72d83933d246484275b1ea227db3fbac81)
[Chasarr](mailto:34444482+Chasarr@users.noreply.github.com) | cmake: add missing space (#4955) | 2020-11-16T19:53:30 | [f8d18031eb6e](https://github.com/tldr-pages/tldr/commit/f8d18031eb6e679df6914c77d271e3453fbd642e)
[Flex Zhong](mailto:chungzh07@gmail.com) | remove cmake -i example (#4159) | 2020-07-08T15:14:46 | [866a4f78a054](https://github.com/tldr-pages/tldr/commit/866a4f78a0549a718d788fa006958f14f9f42260)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | cmake.md: add homepage | 2019-04-15T01:35:17 | [d856fbdef08f](https://github.com/tldr-pages/tldr/commit/d856fbdef08f9fbabf3e655bfaf46056f19be01a)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cmake: use -H -B trick for out-of-src build As initially discussed in #1379. This removes the need to use `mkdir` and `cd`. Inspired [...] | 2017-06-08T06:24:38 | [b4dc9ec224ee](https://github.com/tldr-pages/tldr/commit/b4dc9ec224eef8be44206d2f1e655944b02446f7)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cmake: add mkdir to the out-of-source build ex. | 2017-05-22T21:41:16 | [6b1e4f24ab89](https://github.com/tldr-pages/tldr/commit/6b1e4f24ab89531aab22c7be8a5078804acace92)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cmake: directory --> folder; fix typo | 2017-05-16T12:37:47 | [88eea8611789](https://github.com/tldr-pages/tldr/commit/88eea8611789b901988bfbd7b7ad5342b174f947)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cmake: fix syntax and adjust per code review | 2017-05-04T09:46:54 | [776fdcf77a76](https://github.com/tldr-pages/tldr/commit/776fdcf77a764999697c5bc838d2d82a9c00de68)
[PFCKrutonium](mailto:PFCKrutonium@gmail.com) | cmake: add page (closes #1172) | 2017-05-04T09:46:54 | [d3fed3b31f94](https://github.com/tldr-pages/tldr/commit/d3fed3b31f946c5ab083abc85f53f7ee70587536)

