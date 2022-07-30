---
author: ['Michael Schwarz', 'Stig124', 'Starbeamrainbowlabs']
date: 1636231040
title: "add-apt-repository"
description: "add-apt-repository, Manages apt repository definitions."
categories: "linux"
---
> More information: <https://manned.org/apt-add-repository>.

- Add a new apt repository:

```bash
add-apt-repository repository_spec
```

- Remove an apt repository:

```bash
add-apt-repository --remove repository_spec
```

- Update the package cache after adding a repository:

```bash
add-apt-repository --update repository_spec
```

- Allow source packages to be downloaded from the repository:

```bash
add-apt-repository --enable-source repository_spec
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Michael Schwarz](mailto:contact@micschwarz.dev) | add-apt-repository: improve --enable-source example description (#7203) | 2021-11-06T21:37:20 | [b8dc065280b7](https://github.com/tldr-pages/tldr/commit/b8dc065280b705e128bf0306129855153e70b0dc)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | add-apt-repository: add page (#2244) | 2018-08-21T11:33:37 | [73d32bb5d62e](https://github.com/tldr-pages/tldr/commit/73d32bb5d62ed4f8dcfec73256e2a34e8a93e3d4)

