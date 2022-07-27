---
author: ['Axel Navarro']
date: 1642131234
title: "powerstat, TLDR Pages"
description: "powerstat, Measures the power consumption of a computer that has a battery power source or supports the RAPL interface."
categories: "linux"
---
> More information: <https://manned.org/powerstat>.

- Measure power with the default of 10 samples with an interval of 10 seconds:

```bash
powerstat
```

- Measure power with custom number of samples and interval duration:

```bash
powerstat interval number_of_samples
```

- Measure power using Intel's RAPL interface:

```bash
powerstat -R interval number_of_samples
```

- Show a histogram of the power measurements:

```bash
powerstat -H interval number_of_samples
```

- Enable all statistics gathering options:

```bash
powerstat -a interval number_of_samples
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | check-language-support, faketime, pi, powerstat, rig, xdg-user-dirs-update: update links (#7644) | 2022-01-14T04:33:54 | [d5cfac8d3581](https://github.com/tldr-pages/tldr/commit/d5cfac8d3581cf0f9d735fbcefe9bf3b02815441)

