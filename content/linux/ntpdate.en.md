---
author: ['EduardBaer']
date: 1633831826
title: "ntpdate"
description: "ntpdate, Synchronize and set the date and time via NTP."
categories: "linux"
---
> More information: <http://support.ntp.org/documentation>.

- Synchronize and set date and time:

```bash
sudo ntpdate host
```

- Query the host without setting the time:

```bash
ntpdate -q host
```

- Use an unprivileged port in case a firewall is blocking privileged ports:

```bash
sudo ntpdate -u host
```

- Force time to be stepped using `settimeofday` instead of `slewed`:

```bash
sudo ntpdate -b host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[EduardBaer](mailto:EduardBaer@users.noreply.github.com) | ntpdate: add page (#6856) | 2021-10-10T04:10:26 | [bc872a596599](https://github.com/tldr-pages/tldr/commit/bc872a59659980a534f242adcce44697ae7c1c0d)

