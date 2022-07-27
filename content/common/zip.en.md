---
author: ['Xavi S.B', 'Waldir Pimenta', 'sebastientinel', 'Emily Grace Seville', 'endorama', 'Miles Glapa-Grossklag', 'Agniva De Sarker', 'Ruben Vereecken', 'Being simple', 'Hendrik Elsner', 'Eric Nielsen', 'rprieto', 'mister-ben', 'Seth Falco', 'Jaehoon Choi']
date: 1657140467
title: "zip, TLDR Pages"
description: "zip, Package and compress (archive) files into zip file."
categories: "common"
---
> See also: `unzip`.

> More information: <https://manned.org/zip>.

- Add files/directories to a specific archive:

```bash
zip -r path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Remove files/directories from a specific archive:

```bash
zip -d path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Archive files/directories e[x]cluding specified ones:

```bash
zip path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ... -x path/to/excluded_files_or_directories
```

- Archive files/directories with a specific compression level (`0` - the lowest, `9` - the highest):

```bash
zip -r -0-9 path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Create an [e]ncrypted archive with a specific password:

```bash
zip -r -e path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Archive files/directories to a multi-part [s]plit zip file (e.g. 3 GB parts):

```bash
zip -r -s 3g path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Print a specific archive contents:

```bash
zip -sf path/to/compressed.zip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | zip: add/refresh pages (#7996) | 2022-07-06T22:47:47 | [5e2f4072bce4](https://github.com/tldr-pages/tldr/commit/5e2f4072bce4e1bb1ffc80edd5d5ec223042182a)
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | common/z*: add more information link (#6445) | 2021-09-01T21:08:03 | [82e685e155b9](https://github.com/tldr-pages/tldr/commit/82e685e155b93e19aef385e655da9134d4808701)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[endorama](mailto:endorama@users.noreply.github.com) | zip: add list files example and update first example (#5667) From the `zip` man page: > The -sf show files option can be used to scan [...] | 2021-04-04T13:45:41 | [3597c70e6c4d](https://github.com/tldr-pages/tldr/commit/3597c70e6c4d9b4afc57c52692cdc9703bea7916)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Hendrik Elsner](mailto:321hendrik@gmail.com) | zip: added multi-part zip compression (#1980) | 2018-02-09T11:52:28 | [1f1980517794](https://github.com/tldr-pages/tldr/commit/1f1980517794a210291df38edbbbbc35fa27718c)
[mister-ben](mailto:git@misterben.me) | zip: better password prompt hint | 2017-10-20T14:18:06 | [50b48f60fd95](https://github.com/tldr-pages/tldr/commit/50b48f60fd952d9742a92dba8a186f8dc264620e)
[mister-ben](mailto:git@misterben.me) | zip: explain encryption as password protected | 2017-10-20T13:26:55 | [0fb419869509](https://github.com/tldr-pages/tldr/commit/0fb419869509a6dfb0c2705ad106a4ef718f9af2)
[mister-ben](mailto:git@misterben.me) | zip: add encryption example | 2017-10-20T13:22:59 | [3477ab330ed8](https://github.com/tldr-pages/tldr/commit/3477ab330ed8da9f3b01c1d4abd15e36f2f83341)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | zip: simplify -x example According to the 5th item of the [Guidelines](https://github.com/tldr- [...] | 2017-10-05T23:19:48 | [43ff4dd736a1](https://github.com/tldr-pages/tldr/commit/43ff4dd736a1aba553c6beacb17e09849e97e576)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | zip.md: wrap compression level in tokens | 2017-03-07T19:29:12 | [c0ba2afc2b0a](https://github.com/tldr-pages/tldr/commit/c0ba2afc2b0a71344017f7170db369a4bfb511df)
[Jaehoon Choi](mailto:plaintext@andromedarabbit.net) | `zip`: explain how to specify the compression level | 2017-03-07T19:29:12 | [eee1e72ba2d8](https://github.com/tldr-pages/tldr/commit/eee1e72ba2d8c05e5ddbc5d08b7ccc679e21c007)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | zip: minor change to fix build See #1018 and https://github.com/tldr-pages/tldr-lint/pull/6 | 2016-09-01T22:39:16 | [76783fdc7256](https://github.com/tldr-pages/tldr/commit/76783fdc7256b415f89cabed5fef3f4cd901156c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | zip: improve page (#1030) - reorganize examples for a more logical progression - make descriptions clearer and more in line with the [...] | 2016-09-01T17:41:00 | [be0fbaec973d](https://github.com/tldr-pages/tldr/commit/be0fbaec973d1582be38c8ced94b899fdc4076eb)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Clarify -x option This also makes it easier to understand what `-x` means (eXclude) | 2016-02-21T14:31:36 | [f3ba0e60860e](https://github.com/tldr-pages/tldr/commit/f3ba0e60860e9deb94bbc19c6c738b45fa38f7f6)
[Being simple](mailto:haolin.h0@gmail.com) | modify comment modify comment | 2016-02-21T06:03:30 | [c0869724ac34](https://github.com/tldr-pages/tldr/commit/c0869724ac349573e64a62981b7ed150a36af8ed)
[Being simple](mailto:haolin.h0@gmail.com) | add a zip cmd zip exclude some patterns | 2016-02-20T04:59:18 | [e00f9214ef85](https://github.com/tldr-pages/tldr/commit/e00f9214ef85e980b343df2bdf4066d3933f5a7f)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Xavi S.B](mailto:xavi@typeform.com) | add options to zip | 2015-12-29T00:29:16 | [daf48855363b](https://github.com/tldr-pages/tldr/commit/daf48855363bd8c76c763a51c33b15682497717b)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

