---
author: ['Stig124', 'Lucas Gabriel Schneider', 'Seth Falco', 'Severin Fürbringer']
date: 1629050349
title: "genkernel, TLDR Pages"
description: "genkernel, Gentoo Linux utility to compile and install kernels."
categories: "linux"
---
> More information: <https://wiki.gentoo.org/wiki/Genkernel>.

- Automatically compile and install a generic kernel:

```bash
sudo genkernel all
```

- Build and install the bzImage|initramfs|kernel|ramdisk only:

```bash
sudo genkernel bzImage|initramfs|kernel|ramdisk
```

- Apply changes to the kernel configuration before compiling and installing:

```bash
sudo genkernel --menuconfig all
```

- Generate a kernel with a custom name:

```bash
sudo genkernel --kernname=custom_name all
```

- Use a kernel source outside the default directory `/usr/src/linux`:

```bash
sudo genkernel --kerneldir=path/to/directory all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Severin Fürbringer](mailto:severin@protonmail.ch) | genkernel: add page (#1433) | 2017-07-27T23:21:36 | [3f4742d021de](https://github.com/tldr-pages/tldr/commit/3f4742d021ded2c49766feacdccdd83591b4f4c7)

