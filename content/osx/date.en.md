---
author: ['Waldir Pimenta', 'Emily Grace Seville', 'Agniva De Sarker', 'Kyle', 'Mikey Garcia', 'bl-ue', 'Daniel Compton']
date: 1644837703
title: "date"
description: "date, Set or display the system date."
categories: "osx"
---
> More information: <https://ss64.com/osx/date.html>.

- Display the current date using the default locale's format:

```bash
date +%c
```

- Display the current date in UTC and ISO 8601 format:

```bash
date -u +%Y-%m-%dT%H:%M:%SZ
```

- Display the current date as a Unix timestamp (seconds since the Unix epoch):

```bash
date +%s
```

- Display a specific date (represented as a Unix timestamp) using the default format:

```bash
date -r 1473305798
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Revert "date: fix typo (#4069)" (#5997) | 2021-05-20T18:36:10 | [33b5fcd7bdc9](https://github.com/tldr-pages/tldr/commit/33b5fcd7bdc9e3e169e3a3c5c8b767dcb05b770e)
[Mikey Garcia](mailto:gikeymarcia@gmail.com) | date: fix typo (#4069) | 2020-05-27T05:46:20 | [e0151803205b](https://github.com/tldr-pages/tldr/commit/e0151803205bb7efa1e2222a979580dbcfc19589)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | date: minor fix to sync osx / linux versions | 2016-10-07T00:29:04 | [a35633e60b99](https://github.com/tldr-pages/tldr/commit/a35633e60b99aaa4ddaa90390ce64866d25afc42)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | date.md: another attempt at clarifying the descriptions | 2016-10-06T13:05:12 | [c9c5f9edc528](https://github.com/tldr-pages/tldr/commit/c9c5f9edc528d1a4baebe25109d8e8c82d8c421d)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Update the last example to explain the -r flag | 2016-10-06T06:32:39 | [cf551279355a](https://github.com/tldr-pages/tldr/commit/cf551279355aaf1f3c18ea1a4be24034931bda6e)
[Daniel Compton](mailto:desk@danielcompton.net) | Add unix epoch commands These differ between Linux and OS X so the pages needed to be split. | 2016-09-08T13:00:50 | [8136ac19301b](https://github.com/tldr-pages/tldr/commit/8136ac19301be22a68a91ef60a1bd867cca4cd6c)

