---
author: ['Jonathan Boiser', 'Nelson Figueroa', 'meowmeowcat']
date: 1635858124
title: "pmset, TLDR Pages"
description: "pmset, Configure macOS power management settings, as one might do in System Preferences > Energy Saver."
categories: "osx"
---
> Commands that modify settings must begin with `sudo`.

> More information: <https://ss64.com/osx/pmset.html>.

- Display the current power management settings:

```bash
pmset -g
```

- Display the current power source and battery levels:

```bash
pmset -g batt
```

- Put display to sleep immediately:

```bash
pmset displaysleepnow
```

- Set display to never sleep when on charger power:

```bash
sudo pmset -c displaysleep 0
```

- Set display to sleep after 15 minutes when on battery power:

```bash
sudo pmset -b displaysleep 15
```

- Schedule computer to automatically wake up every weekday at 9 AM:

```bash
sudo pmset repeat wake MTWRF 09:00:00
```

- Restore to system defaults:

```bash
sudo pmset -a displaysleep 10 disksleep 10 sleep 30 womp 1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osascript, xattr, pmset, say, screencapture: add link (#7368) | 2021-11-02T14:02:04 | [b85bc433fb19](https://github.com/tldr-pages/tldr/commit/b85bc433fb1916e6fd9b053f9db24284d11fc4e6)
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | pmset: add displaysleepnow (#4483) | 2020-10-04T22:10:27 | [4779ac10c681](https://github.com/tldr-pages/tldr/commit/4779ac10c681fa8ed2bbf182e6dd6628152476f9)
[Jonathan Boiser](mailto:jboiser@gmail.com) | pmset: simplify description | 2016-10-02T19:50:56 | [35c60098ece9](https://github.com/tldr-pages/tldr/commit/35c60098ece93857e4164cd08c0b613a66d8600e)
[Jonathan Boiser](mailto:jboiser@gmail.com) | pmset: add `sudo` to commands that change settings. | 2016-10-02T16:58:21 | [680fff35efa9](https://github.com/tldr-pages/tldr/commit/680fff35efa99e9ac8af940636a8bcb2d75162bc)
[Jonathan Boiser](mailto:jboiser@gmail.com) | pmset: add page | 2016-10-02T07:06:27 | [54e18a150a97](https://github.com/tldr-pages/tldr/commit/54e18a150a970e20801a8898c531d1bbd47a49ec)

