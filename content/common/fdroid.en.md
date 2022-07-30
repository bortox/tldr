---
author: ['bl-ue', 'Pierre Rudloff']
date: 1621541621
title: "fdroid"
description: "fdroid, F-Droid build tool."
categories: "common"
---
> F-Droid is an installable catalog of FOSS (Free and Open Source Software) applications for the Android platform.

> More information: <https://f-droid.org/>.

- Build a specific app:

```bash
fdroid build app_id
```

- Build a specific app in a build server VM:

```bash
fdroid build app_id --server
```

- Publish the app to the local repository:

```bash
fdroid publish app_id
```

- Install the app on every connected device:

```bash
fdroid install app_id
```

- Check if the metadata is formatted correctly:

```bash
fdroid lint --format app_id
```

- Fix the formatting automatically (if possible):

```bash
fdroid rewritemeta app_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Pierre Rudloff](mailto:contact@rudloff.pro) | fdroid: add page (#3550) | 2019-11-12T11:57:24 | [51e75c278c6e](https://github.com/tldr-pages/tldr/commit/51e75c278c6e92d7400c0dc22b7ca0dfdf70ae62)

