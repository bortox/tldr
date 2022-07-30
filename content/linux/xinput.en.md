---
author: ['Igor Shubovych', 'Jonathan Dahan', 'Jean Lucas', 'Ben Anderson', 'Jezeniel Zapanta', 'Azrael JD']
date: 1643293250
title: "xinput"
description: "xinput, List available input devices, query information about a device and change input device settings."
categories: "linux"
---
> More information: <https://manned.org/xinput>.

- List all input devices:

```bash
xinput list
```

- Disable an input:

```bash
xinput disable id
```

- Enable an input:

```bash
xinput enable id
```

- Disconnect an input from its master:

```bash
xinput float id
```

- Reattach an input as slave to a master:

```bash
xinput reattach id master_id
```

- List settings of an input device:

```bash
xinput list-props id
```

- Change a setting of an input device:

```bash
xinput set-prop id setting_id value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | xinput: add more information link (#7721) | 2022-01-27T15:20:50 | [2353d5fd417f](https://github.com/tldr-pages/tldr/commit/2353d5fd417f4c315e6394cfafdd1c9fcd74ed1f)
[Ben Anderson](mailto:63131015+Ben-D-Anderson@users.noreply.github.com) | xinput: add list-props and set-prop examples (#6205) | 2021-07-08T15:13:59 | [2dc847873b68](https://github.com/tldr-pages/tldr/commit/2dc847873b684dfd6e700c06208bd875ab5d5abf)
[Jonathan Dahan](mailto:hi@jonathan.is) | xinput: add disable/enable commands (#3331) | 2019-10-07T02:43:32 | [37e49657927c](https://github.com/tldr-pages/tldr/commit/37e49657927c4ceb12fd6f8b62c59f9345c72c4e)
[Jezeniel Zapanta](mailto:jpzapanta22@gmail.com) | Fix xinput reattach command | 2016-03-29T02:58:36 | [983145f4434e](https://github.com/tldr-pages/tldr/commit/983145f4434ef30916632e701c6455056f691fa1)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | xinput: linting | 2016-01-17T23:15:21 | [01b952940cf5](https://github.com/tldr-pages/tldr/commit/01b952940cf57831601127d9c119646454062a57)
[Jean Lucas](mailto:jeanleonino@gmail.com) | Update xinput.md | 2015-12-28T20:05:31 | [8cfad8c61a62](https://github.com/tldr-pages/tldr/commit/8cfad8c61a6214e2c780b26e6feb5772645ae140)
[Jean Lucas](mailto:jeanleonino@gmail.com) | Added xinput command for Linux The xinput utility is useful when you want to turn off a input device (laptop keyboard, for example). | 2015-12-28T17:37:52 | [d0e110f17d59](https://github.com/tldr-pages/tldr/commit/d0e110f17d59fd923833836bcf59b4f5e91a3f7c)

