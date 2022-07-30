---
author: ['leekuo']
date: 1658982410
title: "ern"
description: "ern, Electrode Native platform command line client."
categories: "common"
---
> More information: <https://native.electrode.io/reference/index-6>.

- Create a new `ern` application (`MiniApp`):

```bash
ern create-miniapp application_name
```

- Run one or more `MiniApps` in the iOS / Android Runner application:

```bash
ern run-ios|android
```

- Create an Electrode Native container:

```bash
ern create-container --miniapps /path/to/miniapp_directory --platform ios|android
```

- Publish an Electrode Native container to a local Maven repository:

```bash
ern publish-container --publisher maven --platform android --extra '{"groupId":"com.walmart.ern","artifactId":"quickstart"}'
```

- Transform an iOS container into a pre-compiled binary framework:

```bash
ern transform-container --platform ios --transformer xcframework
```

- List all installed versions of Electrode Native:

```bash
ern platform versions
```

- Set a logging level:

```bash
ern platform config set logLevel trace|debug
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[leekuo](mailto:5809175+leekuo@users.noreply.github.com) | ern: add page (#8229) * ern: add page * ern: fix end line colons * ern: update based on review feedback * ern: use infinite tense in [...] | 2022-07-28T06:26:50 | [635fcfc9ae6d](https://github.com/tldr-pages/tldr/commit/635fcfc9ae6d683966a48d1a1421b85ad7d8b4fd)

