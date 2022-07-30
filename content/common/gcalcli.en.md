---
author: ['bl-ue', 'Lee T']
date: 1621541621
title: "gcalcli"
description: "gcalcli, Command-line tool to interact with Google Calendar."
categories: "common"
---
> Requests Google API authorization upon first launch.

> More information: <https://github.com/insanum/gcalcli>.

- List your events for all your calendars over the next 7 days:

```bash
gcalcli agenda
```

- Show events starting from or between specific dates (also takes relative dates e.g. "tomorrow"):

```bash
gcalcli agenda mm/dd [mm/dd]
```

- List events from a specific calendar:

```bash
gcalcli --calendar calendar_name agenda
```

- Display an ASCII calendar of events by week:

```bash
gcalcli calw
```

- Display an ASCII calendar of events for a month:

```bash
gcalcli calm
```

- Quick-add an event to your calendar:

```bash
gcalcli --calendar calendar_name quick "mm/dd HH:MM event_name"
```

- Add an event to calendar. Triggers interactive prompt:

```bash
gcalcli --calendar "calendar_name" add
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lee T](mailto:lee2sman@users.noreply.github.com) | gcalcli: add page (#3253) | 2019-08-23T17:41:47 | [f1d21e030b1d](https://github.com/tldr-pages/tldr/commit/f1d21e030b1d41fe342d3df874df2a54ba1ddff1)

