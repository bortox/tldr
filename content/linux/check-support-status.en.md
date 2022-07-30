---
author: ['Axel Navarro', 'Pierre Rudloff']
date: 1641649180
title: "check-support-status"
description: "check-support-status, Identify installed Debian packages for which support has had to be limited or prematurely ended."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/debian-security-support/check-support-status.html>.

- Display packages whose support is limited, has already ended or will end earlier than the distribution's end of life:

```bash
check-support-status
```

- Display only packages whose support has ended:

```bash
check-support-status --type ended
```

- Skip printing a headline:

```bash
check-support-status --no-heading
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Pierre Rudloff](mailto:contact@rudloff.pro) | check-support-status: add page (#3629) | 2019-11-28T22:24:45 | [95d472d781fd](https://github.com/tldr-pages/tldr/commit/95d472d781fdf72688105c0e7313087e2353f30c)

