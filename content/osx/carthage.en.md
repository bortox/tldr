---
author: ['Waldir Pimenta', 'Jeef', 'Kyle']
date: 1629747204
title: "carthage"
description: "carthage, A dependency management tool for Cocoa applications."
categories: "osx"
---
> More information: <https://github.com/Carthage/Carthage>.

- Download the latest version of all dependencies mentioned in Cartfile, and build them:

```bash
carthage update
```

- Update dependencies, but only build for iOS:

```bash
carthage update --platform ios
```

- Update dependencies, but don't build any of them:

```bash
carthage update --no-build
```

- Download and rebuild the current version of dependencies (without updating them):

```bash
carthage bootstrap
```

- Rebuild a specific dependency:

```bash
carthage build dependency
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | carthage: description tweaks | 2017-04-23T16:25:45 | [6fc1a2234beb](https://github.com/tldr-pages/tldr/commit/6fc1a2234beb2c1e7545cb17b58644dd95b66992)
[Jeef](mailto:jeeftor@users.noreply.github.com) | carthage.md: add page (#1278) | 2017-03-01T05:54:20 | [c10d09d0bdda](https://github.com/tldr-pages/tldr/commit/c10d09d0bdda5daec4a3a64f6d05c3465494a59d)

