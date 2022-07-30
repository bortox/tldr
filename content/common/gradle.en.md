---
author: ['Waldir Pimenta', 'Schneider', 'Nicolas Kosinski', 'Wilhelm Haas', 'lagel', 'pxgamer', 'Marco Bonelli', 'Ruben Vereecken']
date: 1626957133
title: "gradle"
description: "gradle, Gradle is an open source build automation system."
categories: "common"
---
> More information: <https://gradle.org>.

- Compile a package:

```bash
gradle build
```

- Exclude test task:

```bash
gradle build -x test
```

- Run in offline mode to prevent Gradle from accessing the network during builds:

```bash
gradle build --offline
```

- Clear the build directory:

```bash
gradle clean
```

- Build an Android Package (APK) in release mode:

```bash
gradle assembleRelease
```

- List the main tasks:

```bash
gradle tasks
```

- List all the tasks:

```bash
gradle tasks --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | gradle: edit assembleRelease example to show Android Studio specificity (#6194) 'assembleDebug' and 'assembleRelease' tasks are [...] | 2021-07-22T14:32:13 | [1c050a6e38c5](https://github.com/tldr-pages/tldr/commit/1c050a6e38c5efc26b271409f6892c5013dfce40)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | gradle: add tasks examples (#5889) | 2021-05-06T17:23:16 | [c9ca880ee9a8](https://github.com/tldr-pages/tldr/commit/c9ca880ee9a8cf67a73814662734997df0a581d6)
[Schneider](mailto:lucas.schneider@sap.com) | multiple pages: rephrase without adjectives | 2019-10-13T05:28:04 | [42152ed45923](https://github.com/tldr-pages/tldr/commit/42152ed459230c2b244529f0c5990335e0057c6c)
[pxgamer](mailto:owzie123@gmail.com) | gradle: add link to homepage | 2019-06-07T23:58:59 | [ea9a77e3793b](https://github.com/tldr-pages/tldr/commit/ea9a77e3793b3311d92fdb0fbe2b1cd44e3231ca)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Wilhelm Haas](mailto:wilhelm.haas@bavaga.com) | integrates feedback of the reviewer | 2017-12-11T21:13:19 | [e1c6d7c4a617](https://github.com/tldr-pages/tldr/commit/e1c6d7c4a617b44c71e21463b987b03eb4254610)
[Wilhelm Haas](mailto:wilhelm.haas@bavaga.com) | gradle: adds additional gradle examples | 2017-11-29T16:04:45 | [82b32e4549a3](https://github.com/tldr-pages/tldr/commit/82b32e4549a380cafa0df366dd509f4c416654de)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | page format: lowercase command names consistently (#1083) | 2016-09-22T09:03:38 | [107248374447](https://github.com/tldr-pages/tldr/commit/1072483744475ab5a25c87e8eb7ed10c99dd6ed8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lagel](mailto:lagel@live.com) | Add gradle commands | 2015-12-31T02:29:12 | [27b2bfac5443](https://github.com/tldr-pages/tldr/commit/27b2bfac54437bf13812134c5640a955cee464ec)

