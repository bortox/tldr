---
author: ['Ben Scattergood', 'bl-ue', 'marchersimon']
date: 1621541621
title: "balena, TLDR Pages"
description: "balena, Interact with the balenaCloud, openBalena and the balena API from the command-line."
categories: "common"
---
> More information: <https://www.balena.io/docs/reference/cli/>.

- Log in to the balenaCloud account:

```bash
balena login
```

- Create a balenaCloud or openBalena application:

```bash
balena app create app_name
```

- List all balenaCloud or openBalena applications within the account:

```bash
balena apps
```

- List all devices associated with the balenaCloud or openBalena account:

```bash
balena devices
```

- Flash a balenaOS image to a local drive:

```bash
balena local flash path/to/balenaos.img --drive drive_location
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[Ben Scattergood](mailto:benscattergood@gmail.com) | Balena: add page (#3422) | 2019-10-17T18:18:12 | [8eed43ae1a61](https://github.com/tldr-pages/tldr/commit/8eed43ae1a61a712c4fd87aa035322e7223cce25)

