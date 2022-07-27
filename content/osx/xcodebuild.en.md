---
author: ['pixel', 'Waldir Pimenta']
date: 1644810209
title: "xcodebuild, TLDR Pages"
description: "xcodebuild, Build Xcode projects."
categories: "osx"
---
> More information: <https://developer.apple.com/library/archive/technotes/tn2339/_index.html>.

- Build workspace:

```bash
xcodebuild -workspace workspace_name.workspace -scheme scheme_name -configuration configuration_name clean build SYMROOT=SYMROOT_path
```

- Build project:

```bash
xcodebuild -target target_name -configuration configuration_name clean build SYMROOT=SYMROOT_path
```

- Show SDKs:

```bash
xcodebuild -showsdks
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | networksetup, port, xcode-select, xcodebuild: add more information links (#7754) * port: more info * xcodebuild: more info * xcode- [...] | 2022-02-14T04:43:29 | [4e2c525e311a](https://github.com/tldr-pages/tldr/commit/4e2c525e311a327155c32b467b5ff24b8df22318)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | xcodebuild.md: add page (#1008) * Create xcodebuild.md xcodebuild * xcodebuild.md: shorten page * xcodebuild.md: use token formatting [...] | 2016-08-21T12:59:23 | [04f25d3684b4](https://github.com/tldr-pages/tldr/commit/04f25d3684b48b6d50d6ca95e6c9e72ba960450d)

