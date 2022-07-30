---
author: ['Managor', 'bl-ue', 'CleanMachine1', 'Finermeerkat137']
date: 1640557014
title: "makepkg"
description: "makepkg, Create a package which can be used with `pacman`."
categories: "linux"
---
> Uses the `PKGBUILD` file in the current working directory by default.

> More information: <https://man.archlinux.org/man/makepkg.8>.

- Make a package:

```bash
makepkg
```

- Make a package and install its dependencies:

```bash
makepkg --syncdeps
```

- Make a package, install its dependencies then install it to the system:

```bash
makepkg --syncdeps --install
```

- Make a package, but skip checking the source's hashes:

```bash
makepkg --skipchecksums
```

- Clean up work directories after a successful build:

```bash
makepkg --clean
```

- Verify the hashes of the sources:

```bash
makepkg --verifysource
```

- Generate and save the source information into `.SRCINFO`:

```bash
makepkg --printsrcinfo > .SRCINFO
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | makepkg: fix command to match standard (#7579) * makepkg: fix command to match standard * add \n | 2021-12-26T23:16:54 | [1a6a1759bddb](https://github.com/tldr-pages/tldr/commit/1a6a1759bddb0ff2659d8aa011179cbfb71f5bb4)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | makepkg: add commands (#7577) | 2021-12-26T16:58:12 | [32ad43191906](https://github.com/tldr-pages/tldr/commit/32ad43191906369e1f124ae408bfb3610c0e9235)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | makepkg: refresh (#7499) | 2021-12-05T22:31:22 | [a7c60a0e91bf](https://github.com/tldr-pages/tldr/commit/a7c60a0e91bf4d5006c9e9f57302f987e6e32874)
[Managor](mailto:42655600+Managor@users.noreply.github.com) | makepkg: add clean option (#6540) | 2021-09-16T21:27:17 | [9899a25197f5](https://github.com/tldr-pages/tldr/commit/9899a25197f5c99670f767eae76245d4df7fcb93)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Finermeerkat137](mailto:sudhip@nashi.us) | makepkg: add page (#4140) | 2020-07-05T22:46:19 | [8c86156d1305](https://github.com/tldr-pages/tldr/commit/8c86156d13050d1d886c4e6d3f5f5c1f458b9645)

