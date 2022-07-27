---
author: ['Stig124', 'evaleries', 'Niklas', 'Guido Lena Cota']
date: 1625841955
title: "flatpak, TLDR Pages"
description: "flatpak, Build, install and run flatpak applications and runtimes."
categories: "linux"
---
> More information: <https://docs.flatpak.org/en/latest/flatpak-command-reference.html#flatpak>.

- Run an installed application:

```bash
flatpak run name
```

- Install an application from a remote source:

```bash
flatpak install remote name
```

- List all installed applications and runtimes:

```bash
flatpak list
```

- Update all installed applications and runtimes:

```bash
flatpak update
```

- Add a remote source:

```bash
flatpak remote-add --if-not-exists remote_name remote_url
```

- List all configured remote sources:

```bash
flatpak remote-list
```

- Remove an installed application:

```bash
flatpak remove name
```

- Show information about an installed application:

```bash
flatpak info name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[evaleries](mailto:48923153+evaleries@users.noreply.github.com) | flatpak: add info and remove examples (#5422) | 2021-03-27T15:36:20 | [547de5fafaa0](https://github.com/tldr-pages/tldr/commit/547de5fafaa0519483df354b5e78cad98dbebea9)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mass change: apply snake case to tokens (#2518) | 2018-10-29T12:14:25 | [18370557b25e](https://github.com/tldr-pages/tldr/commit/18370557b25e5340d9ee5cfeee346ce8fcb4ef95)
[Niklas](mailto:niklas@ytvwld.de) | flatpak: add page (#2316) | 2018-09-09T16:07:43 | [638b1d45edee](https://github.com/tldr-pages/tldr/commit/638b1d45edee0c0e1816fc891019953485a991d2)

