---
author: ['Patrice Denis', 'Dario Vladović', 'siavashsoleymani', 'lord63', 'Jacob Roeland', 'Eric Nielsen', 'Brian Blaylock', 'Emily Grace Seville', 'Ruben Vereecken', 'Agniva De Sarker', 'Waldir Pimenta', 'marchersimon', 'Matthew Thompson', 'Marco Bonelli']
date: 1659755519
title: "chmod"
description: "chmod, Change the access permissions of a file or directory."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/chmod>.

- Give the [u]ser who owns a file the right to e[x]ecute it:

```bash
chmod u+x path/to/file
```

- Give the [u]ser rights to [r]ead and [w]rite to a file/directory:

```bash
chmod u+rw path/to/file_or_directory
```

- Remove e[x]ecutable rights from the [g]roup:

```bash
chmod g-x path/to/file
```

- Give [a]ll users rights to [r]ead and e[x]ecute:

```bash
chmod a+rx path/to/file
```

- Give [o]thers (not in the file owner's group) the same rights as the [g]roup:

```bash
chmod o=g path/to/file
```

- Remove all rights from [o]thers:

```bash
chmod o= path/to/file
```

- Change permissions recursively giving [g]roup and [o]thers the ability to [w]rite:

```bash
chmod -R g+w,o+w path/to/directory
```

- Recursively give [a]ll users [r]ead permissions to files and e[X]ecute permissions to sub-directories within a directory:

```bash
chmod -R a+rX path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | chmod: update placeholders in examples (#8300) | 2022-08-06T05:11:59 | [4abe09f8b3c8](https://github.com/tldr-pages/tldr/commit/4abe09f8b3c86137ec7cef090574b1578d89290b)
[Brian Blaylock](mailto:blaylockbk@users.noreply.github.com) | chmod: add a+rX example (#6457) | 2021-09-03T22:43:28 | [96306c0c946e](https://github.com/tldr-pages/tldr/commit/96306c0c946e8d4c3e8e05acc47797f2f70a8dc2)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chmod: change more information link (#5547) | 2021-03-29T22:28:18 | [db38dff0e9db](https://github.com/tldr-pages/tldr/commit/db38dff0e9db1d880e7406df340d16509470fbbb)
[Patrice Denis](mailto:patrice.denis@gmail.com) | chmod: add more info link and update French translation (#5496) | 2021-03-24T23:00:22 | [f45463dbd074](https://github.com/tldr-pages/tldr/commit/f45463dbd07431a1fee2763ae4d1f1900d517864)
[siavashsoleymani](mailto:siavash.solimanii@yahoo.com) | chmod: fix typo | 2020-10-27T12:01:11 | [f463df18835a](https://github.com/tldr-pages/tldr/commit/f463df18835a65eeaeae838c12a077d559d6c5e9)
[Jacob Roeland](mailto:jacob@jacroe.com) | chmod: remove all rights (#3748) * chmod: remove all rights * chmod: consistent bracket use | 2020-01-11T23:10:48 | [b289e56fc44b](https://github.com/tldr-pages/tldr/commit/b289e56fc44b43e4adc9b4e44a5787452ac7a8ac)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: add missing `or_directory` where needed. This commit adds the missing `_or_directory` to any example which is specifying an [...] | 2019-02-08T20:43:24 | [f79f6011e0f2](https://github.com/tldr-pages/tldr/commit/f79f6011e0f298311848b5f38d66c309d4b92665)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | chmod: remove square brackets around "recursively" | 2017-11-30T04:26:20 | [42b679e93ba8](https://github.com/tldr-pages/tldr/commit/42b679e93ba880ecbbdb4a698414ace74b6fe0c4)
[Matthew Thompson](mailto:fortran@gmail.com) | Update chmod.md Add example avoiding `X` | 2017-11-30T01:05:58 | [9d11a1a38ef7](https://github.com/tldr-pages/tldr/commit/9d11a1a38ef74334293613fe658ebbbd4076cafd)
[Matthew Thompson](mailto:fortran@gmail.com) | Update chmod.md: Add recursive chmod Might not be approved, but this is the classic 755 on all directories, 644 on all files in a tree [...] | 2017-11-24T15:01:12 | [474ca28ff173](https://github.com/tldr-pages/tldr/commit/474ca28ff1735fc0b127fb1365ff55eed9bc9d76)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | chmod: Use brackets instead of parenthesis (#1024) To specify with single-letter parameter is being referenced (as per #1018) | 2016-08-30T18:47:11 | [c8e3e4490540](https://github.com/tldr-pages/tldr/commit/c8e3e449054003363683dddd389cdf825d1afddb)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Create chmod.md loosely based on the proposal at #140 | 2014-10-02T04:39:28 | [5404e5d43238](https://github.com/tldr-pages/tldr/commit/5404e5d4323835c45825ce23240c71ae99d76f9e)

