---
author: ['adamoudad']
date: 1658919948
title: "xdg-settings, TLDR Pages"
description: "xdg-settings, Manage settings of XDG-compatible desktop environments."
categories: "linux"
---
> More information: <https://portland.freedesktop.org/doc/xdg-settings.html>.

- Print the default web browser:

```bash
xdg-settings get default-web-browser
```

- Set the default web browser to Firefox:

```bash
xdg-settings set default-web-browser firefox.desktop
```

- Set the default mail URL scheme handler to Evolution:

```bash
xdg-settings set default-url-scheme-handler mailto evolution.desktop
```

- Set the default PDF document viewer:

```bash
xdg-settings set pdf-viewer.desktop
```

- Display help:

```bash
xdg-settings --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[adamoudad](mailto:adam.oudad@gmail.com) | xdg-settings: add page (#8215) | 2022-07-27T13:05:48 | [9619e5379ba5](https://github.com/tldr-pages/tldr/commit/9619e5379ba5089c5c9a7f3d9fb670ffcb429cbb)

