---
author: ['Responsible', 'aherst', 'Matt C', 'Ruben Vereecken', 'hellojukay', 'rprieto', 'Axel Navarro']
date: 1633744829
title: "systemctl, TLDR Pages"
description: "systemctl, Control the systemd system and service manager."
categories: "linux"
---
> More information: <https://www.freedesktop.org/software/systemd/man/systemctl.html>.

- Show all running services:

```bash
systemctl status
```

- List failed units:

```bash
systemctl --failed
```

- Start/Stop/Restart/Reload a service:

```bash
systemctl start|stop|restart|reload unit
```

- Show the status of a unit:

```bash
systemctl status unit
```

- Enable/Disable a unit to be started on bootup:

```bash
systemctl enable|disable unit
```

- Mask/Unmask a unit to prevent enablement and manual activation:

```bash
systemctl mask|unmask unit
```

- Reload systemd, scanning for new or changed units:

```bash
systemctl daemon-reload
```

- Check if a unit is enabled:

```bash
systemctl is-enabled unit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Matt C](mailto:mcompton2002@gmail.com) | systemctl: add global status example (#6849) | 2021-10-09T04:00:29 | [0eb3f5544758](https://github.com/tldr-pages/tldr/commit/0eb3f55447589910641b08d11a0e077595a4c0dd)
[Axel Navarro](mailto:navarroaxel@gmail.com) | systemctl: fix example description caps (#5281) | 2021-02-21T03:00:15 | [424d2ed45a1e](https://github.com/tldr-pages/tldr/commit/424d2ed45a1ee00949aca4ef18655d45952e11d7)
[Axel Navarro](mailto:navarroaxel@gmail.com) | systemctl: fix token syntax for multicommand examples (#5274) | 2021-02-19T11:13:45 | [a808abf3db73](https://github.com/tldr-pages/tldr/commit/a808abf3db7319da4a08571d435057b5190561c7)
[aherst](mailto:adamherst@adamherst.com) | systemctl: improve mask/unmask example description (#5270) | 2021-02-17T20:56:30 | [a6984a88bf88](https://github.com/tldr-pages/tldr/commit/a6984a88bf8833cc9a87e3a7192abecbc1565988)
[hellojukay](mailto:hellojukay@163.com) | systemctl: add is-active and is-enabled examples (#4282) | 2020-09-01T16:31:47 | [aab149bc7bb4](https://github.com/tldr-pages/tldr/commit/aab149bc7bb4f5274b8ad3f6bb3ee15ebc9a5e6d)
[Responsible](mailto:responsible@users.noreply.github.com) | Update systemctl.md; add page of systemd-analyze (#844) | 2016-04-10T00:36:11 | [1bafef40fabb](https://github.com/tldr-pages/tldr/commit/1bafef40fabbf050b18eb767ac6b834635bf5610)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

