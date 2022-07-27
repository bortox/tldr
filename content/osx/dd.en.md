---
author: ['Kyle', 'William', 'Ruben Vereecken', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629747204
title: "dd, TLDR Pages"
description: "dd, Convert and copy a file."
categories: "osx"
---
> More information: <https://ss64.com/osx/dd.html>.

- Make a bootable USB drive from an isohybrid file (such like `archlinux-xxx.iso`):

```bash
dd if=file.iso of=/dev/usb_drive
```

- Clone a drive to another drive with 4 MB block and ignore error:

```bash
dd if=/dev/source_drive of=/dev/dest_drive bs=4m conv=noerror
```

- Generate a file of 100 random bytes by using kernel random driver:

```bash
dd if=/dev/urandom of=random_file bs=100 count=1
```

- Benchmark the write performance of a disk:

```bash
dd if=/dev/zero of=file_1GB bs=1024 count=1000000
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[William](mailto:wang.lp@outlook.com) | add dd.md for osx and linux | 2015-12-29T06:44:27 | [9b421535ddff](https://github.com/tldr-pages/tldr/commit/9b421535ddffcafc00246bc0a683b04f39c25f65)

