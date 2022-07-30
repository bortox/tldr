---
author: ['sidahmed-malaoui', 'Seth Falco']
date: 1629050349
title: "dcfldd"
description: "dcfldd, Enhanced version of dd for forensics and security."
categories: "common"
---
> More information: <http://dcfldd.sourceforge.net/>.

- Copy a disk to a raw image file and hash the image using SHA256:

```bash
dcfldd if=/dev/disk_device of=file.img hash=sha256 hashlog=file.hash
```

- Copy a disk to a raw image file, hashing each 1 GB chunk:

```bash
dcfldd if=/dev/disk_device of=file.img hash=sha512|sha384|sha256|sha1|md5 hashlog=file.hash hashwindow=1G
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[sidahmed-malaoui](mailto:sb.malaoui@gmail.com) | dcfldd: improve an example (#3758) | 2020-01-14T23:02:10 | [147d4811093a](https://github.com/tldr-pages/tldr/commit/147d4811093ae11bf7a332d9561788332ac39c81)
[sidahmed-malaoui](mailto:sb.malaoui@gmail.com) | dcfldd: add page (#3719) | 2020-01-06T17:32:45 | [df2826e26f54](https://github.com/tldr-pages/tldr/commit/df2826e26f541f7c58710b4720632e38945108fd)

