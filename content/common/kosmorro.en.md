---
author: ['Jérôme Deuchnord']
date: 1602128683
title: "kosmorro"
description: "kosmorro, Compute the ephemerides and the events for a given date, at a given position on Earth."
categories: "common"
---
> More information: <http://kosmorro.space>.

- Get ephemerides for Paris, France:

```bash
kosmorro --latitude=48.7996 --longitude=2.3511
```

- Get ephemerides for Paris, France, in the UTC+2 timezone:

```bash
kosmorro --latitude=48.7996 --longitude=2.3511 --timezone=2
```

- Get ephemerides for Paris, France, on June 9th, 2020:

```bash
kosmorro --latitude=48.7996 --longitude=2.3511 --date=2020-06-09
```

- Generate a PDF (note: TeXLive must be installed):

```bash
kosmorro --format=pdf --output=path/to/file.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jérôme Deuchnord](mailto:Deuchnord@users.noreply.github.com) | kosmorro: add page (#4498) | 2020-10-08T05:44:43 | [d51d17a5570f](https://github.com/tldr-pages/tldr/commit/d51d17a5570feee4cb785467384a0c5f9ddea5cd)

