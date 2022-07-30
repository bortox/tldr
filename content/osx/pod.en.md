---
author: ['SimMan', 'Waldir Pimenta', 'Emily Grace Seville']
date: 1644837703
title: "pod"
description: "pod, Dependency manager for Swift and Objective-C Cocoa projects."
categories: "osx"
---
> More information: <https://guides.cocoapods.org/terminal/commands.html>.

- Create a Podfile for the current project with the default contents:

```bash
pod init
```

- Download and install all pods defined in the Podfile (that haven't been installed before):

```bash
pod install
```

- List all available pods:

```bash
pod list
```

- Show the outdated pods (of those currently installed):

```bash
pod outdated
```

- Update all currently installed pods to their newest version:

```bash
pod update
```

- Update a specific (previously installed) pod to its newest version:

```bash
pod update pod_name
```

- Remove CocoaPods from a Xcode project:

```bash
pod deintegrate xcode_project
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | pod.md: improve example descriptions | 2016-08-18T13:19:54 | [948bea2207ab](https://github.com/tldr-pages/tldr/commit/948bea2207ab35773986a191811bb43a4cbaba82)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | pod.md: remove incorrect example and add 'pod list' instead | 2016-08-18T13:19:25 | [9a3906ecbbb3](https://github.com/tldr-pages/tldr/commit/9a3906ecbbb32df787087dcb91198566d4d4ab55)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | expand pod.md page as discussed in #583 | 2016-08-17T20:42:19 | [2f6388423bd1](https://github.com/tldr-pages/tldr/commit/2f6388423bd1004f906a6e9b09243331ad4e5399)
[SimMan](mailto:liwei0990@gmail.com) | Rename pod to pod.md | 2016-08-17T20:31:41 | [dcf58acecd49](https://github.com/tldr-pages/tldr/commit/dcf58acecd490b64a00e89cb6654474c564c5e96)

