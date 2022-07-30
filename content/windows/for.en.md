---
author: ['Emily Grace Seville']
date: 1640090938
title: "for"
description: "for, Conditionally execute a command several times."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/for>.

- Execute given commands for the specified set:

```bash
for %variable in (item_a item_b item_c) do (echo Loop is executed)
```

- Iterate over a given range of numbers:

```bash
for /l %variable in (from, step, to) do (echo Loop is executed)
```

- Iterate over a given list of files:

```bash
for %variable in (file_a.ext file_b.ext file_c.ext) do (echo Loop is executed)
```

- Iterate over a given list of directories:

```bash
for /d %variable in (directory_a/ directory_b/ directory_c/) do (echo Loop is executed)
```

- Perform a given command in every directory:

```bash
for /d %variable in (*) do (if exist %variable echo Loop is executed)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | for: refresh page (#7535) | 2021-12-21T13:48:58 | [dede3e7041a2](https://github.com/tldr-pages/tldr/commit/dede3e7041a2edc5d3e5244c99ac6838600a1b56)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | for: add page (#7442) | 2021-12-12T15:29:08 | [6920317eec97](https://github.com/tldr-pages/tldr/commit/6920317eec97680057f854572bd9ebd4f92becc7)

