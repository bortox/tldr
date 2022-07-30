---
author: ['bl-ue', 'Patrice Denis', 'Starbeamrainbowlabs', 'marchersimon']
date: 1621541621
title: "apt-file"
description: "apt-file, Search for files in apt packages, including ones not yet installed."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/apt-file/apt-file.1.html>.

- Update the metadata database:

```bash
sudo apt update
```

- Search for packages that contain the specified file or path:

```bash
apt-file search|find part/of/filename
```

- List the contents of a specific package:

```bash
apt-file show|list package_name
```

- Search for packages that match the regular expression given in `pattern`:

```bash
apt-file search|find --regexp regular_expression
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | apt-file: add page (#2640) | 2018-12-14T08:09:12 | [26f036496c41](https://github.com/tldr-pages/tldr/commit/26f036496c41d193385dc5a3463375e6f50065cf)

