---
author: ['Azrael JD', 'trk']
date: 1643293322
title: "xclock, TLDR Pages"
description: "xclock, Display the time in analog or digital form."
categories: "linux"
---
> More information: <https://manned.org/xclock>.

- Display an analog clock:

```bash
xclock
```

- Display a 24-hour digital clock with the hour and minute fields only:

```bash
xclock -digital -brief
```

- Display a digital clock using an strftime format string (see strftime(3)):

```bash
xclock -digital -strftime format
```

- Display a 24-hour digital clock with the hour, minute and second fields that updates every second:

```bash
xclock -digital -strftime '%H:%M:%S' -update 1
```

- Display a 12-hour digital clock with the hour and minute fields only:

```bash
xclock -digital -twelve -brief
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | xclock: add more information link (#7719) | 2022-01-27T15:22:02 | [3feb67453d1a](https://github.com/tldr-pages/tldr/commit/3feb67453d1a5eb637095b597136f0d6db392d72)
[trk](mailto:dev.trk.9001@gmail.com) | xclock: add page (#4224) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> Co-authored-by: Zlatan Vasović [...] | 2020-07-28T16:31:18 | [37ec59449a1e](https://github.com/tldr-pages/tldr/commit/37ec59449a1ea2d389fee929fc4e38150892c5b2)

