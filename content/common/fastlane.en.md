---
author: ['Axel Navarro']
date: 1609243025
title: "fastlane"
description: "fastlane, Build and release mobile applications from the command-line."
categories: "common"
---
> More information: <https://docs.fastlane.tools/actions/>.

- Build and sign the iOS application in the current directory:

```bash
fastlane run build_app
```

- Run `pod install` for the project in the current directory:

```bash
fastlane run cocoapods
```

- Delete the derived data from Xcode:

```bash
fastlane run clear_derived_data
```

- Remove the cache for pods:

```bash
fastlane run clean_cocoapods_cache
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | fastlane: add page (#5034) | 2020-12-29T12:57:05 | [2ee8662bd137](https://github.com/tldr-pages/tldr/commit/2ee8662bd137d61295fd9057d4f459d0cc982af8)

