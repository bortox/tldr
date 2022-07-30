---
author: ['Zlatan Vasović', 'Owen Voke', 'Lucas Gabriel Schneider', 'd0gey', 'bl-ue']
date: 1609710376
title: "shutdown"
description: "shutdown, A tool for shutting down, restarting or logging off a machine."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/shutdown>.

- Shutdown the current machine:

```bash
shutdown /s
```

- Shutdown the current machine force-closing all apps:

```bash
shutdown /s /f
```

- Restart the current machine immediately:

```bash
shutdown /r /t 0
```

- Hibernate the current machine:

```bash
shutdown /h
```

- Log off the current machine:

```bash
shutdown /l
```

- Specify a timeout in seconds to wait before shutting down:

```bash
shutdown /s /t seconds
```

- Abort a shutdown sequence whose timeout is yet to expire:

```bash
shutdown /a
```

- Shutdown a remote machine:

```bash
shutdown /m \\hostname
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | windows/shutdown: remove extra example; improve restart example (#5076) | 2021-01-03T22:46:16 | [dbe3717463e0](https://github.com/tldr-pages/tldr/commit/dbe3717463e0eca49a46bd98b1ce85922fd5ec2f)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | Remove the least important example | 2019-12-15T05:59:24 | [c2fd1ddb227f](https://github.com/tldr-pages/tldr/commit/c2fd1ddb227fb10dec9f23cab88410f940340acc)
[d0gey](mailto:44307598+d0gey@users.noreply.github.com) | Add force to shutdown | 2019-12-15T05:59:24 | [aef19f9761e6](https://github.com/tldr-pages/tldr/commit/aef19f9761e6ead738f2b9fff2ba459138fc55c3)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | shutdown: add page (#2449) | 2018-10-16T19:31:49 | [aaedbfef0b54](https://github.com/tldr-pages/tldr/commit/aaedbfef0b54a44c1a2671571a3b91e3c1cbbb3e)

