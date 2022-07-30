---
author: ['Emily Grace Seville']
date: 1643507921
title: "if"
description: "if, Performs conditional processing in batch scripts."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/if>.

- Execute the specified commands if the condition is true:

```bash
if condition (echo Condition is true)
```

- Execute the specified commands if the condition is false:

```bash
if not condition (echo Condition is true)
```

- Execute the first specified commands if the condition is true otherwise execute the second specified commands:

```bash
if condition (echo Condition is true) else (echo Condition is false)
```

- Check whether `%errorlevel%` is greater than or equal to the specified exit code:

```bash
if errorlevel exit_code (echo Condition is true)
```

- Check whether two strings are equal:

```bash
if %variable% == string (echo Condition is true)
```

- Check whether two strings are equal without respecting letter case:

```bash
if /i %variable% == string (echo Condition is true)
```

- Check whether a file exist:

```bash
if exist path/to/file (echo Condition is true)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | Use variables instead of literal values: (#7531) - there is no need to compare two string literals | 2022-01-30T02:58:41 | [c10199cd1ae1](https://github.com/tldr-pages/tldr/commit/c10199cd1ae1d66f35a7db947c3cfaa7914318c1)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | if: add page (#7443) | 2021-12-11T05:30:29 | [2f636d094e24](https://github.com/tldr-pages/tldr/commit/2f636d094e247a68bb3ab38ce9aec43f13f648a9)

