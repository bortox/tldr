---
author: ['warpigsir', 'Bhargav Das Gupta', 'Stig124']
date: 1641208872
title: "enum4linux"
description: "enum4linux, Tool for enumerating Windows and Samba information from remote systems."
categories: "linux"
---
> It attempts to offer similar functionality to enum.exe formerly available from www.bindview.com.

> More information: <https://labs.portcullis.co.uk/tools/enum4linux/>.

- Try to enumerate using all methods:

```bash
enum4linux -a remote_host
```

- Enumerate using given login credentials:

```bash
enum4linux -u user_name -p password remote_host
```

- List usernames from a given host:

```bash
enum4linux -U remote_host
```

- List shares:

```bash
enum4linux -S remote_host
```

- Get OS information:

```bash
enum4linux -o remote_host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bhargav Das Gupta](mailto:47706967+Hephaestus14089@users.noreply.github.com) | cat: fix typo (#7610) | 2022-01-03T12:21:12 | [f4252bd555a6](https://github.com/tldr-pages/tldr/commit/f4252bd555a6ad653684d863e1ef77687dc8f2fd)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[warpigsir](mailto:21257844+warpigsir@users.noreply.github.com) | enum4linux: add page (#3810) | 2020-02-09T22:26:51 | [3573da9e2ba3](https://github.com/tldr-pages/tldr/commit/3573da9e2ba32c85a9aa78cd62fd8cac0e747dcb)

