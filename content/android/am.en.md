---
author: ['Pierre Rudloff', 'Seth Falco']
date: 1629050349
title: "am, TLDR Pages"
description: "am, Android activity manager."
categories: "android"
---
> More information: <https://developer.android.com/studio/command-line/adb#am>.

- Start a specific activity:

```bash
am start -n com.android.settings/.Settings
```

- Start an activity and pass data to it:

```bash
am start -a android.intent.action.VIEW -d tel:123
```

- Start an activity matching a specific action and category:

```bash
am start -a android.intent.action.MAIN -c android.intent.category.HOME
```

- Convert an intent to a URI:

```bash
am to-uri -a android.intent.action.VIEW -d tel:123
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Pierre Rudloff](mailto:contact@rudloff.pro) | am, cmd, dalvikvm, settings: add page (#5481) | 2021-03-25T22:57:15 | [59ca98f7df99](https://github.com/tldr-pages/tldr/commit/59ca98f7df994e7642d21691cfe80e478c67bf3a)

