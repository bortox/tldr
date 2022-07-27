---
author: ['Iksas', 'CleanMachine1', 'Robert Buchberger']
date: 1650786257
title: "pihole, TLDR Pages"
description: "pihole, Terminal interface for the Pi-hole ad-blocking DNS server."
categories: "linux"
---
> More information: <https://docs.pi-hole.net/core/pihole-command/>.

- Check the Pi-hole daemon's status:

```bash
pihole status
```

- Update Pi-hole and Gravity:

```bash
pihole -up
```

- Monitor detailed system status:

```bash
pihole chronometer
```

- Start or stop the daemon:

```bash
pihole enable|disable
```

- Restart the daemon (not the server itself):

```bash
pihole restartdns
```

- Whitelist or blacklist a domain:

```bash
pihole whitelist|blacklist example.com
```

- Search the lists for a domain:

```bash
pihole query example.com
```

- Open a real-time log of connections:

```bash
pihole tail
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Iksas](mailto:Iksas@users.noreply.github.com) | pihole: update more information link (#8045) | 2022-04-24T09:44:17 | [013c2fc1944b](https://github.com/tldr-pages/tldr/commit/013c2fc1944b40c2304bab449c316240f8b5bca5)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | pihole: add examples (#6189) | 2021-07-02T21:29:24 | [c5b0987e78ac](https://github.com/tldr-pages/tldr/commit/c5b0987e78ac92d05f0f60313e8855616da2d624)
[Robert Buchberger](mailto:robert@buchberger.cc) | pihole: add page (#3091) | 2019-06-07T23:56:19 | [d8efdc142cea](https://github.com/tldr-pages/tldr/commit/d8efdc142cea289cc4e1c40fa191c4087712826d)

