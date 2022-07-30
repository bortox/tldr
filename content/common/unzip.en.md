---
author: ['Brian Choromanski', 'Waldir Pimenta', 'Wolfgang Lutz', 'Agniva De Sarker', 'sebastientinel', 'Lucas Gabriel Schneider', 'WrathZA', 'rprieto', 'Xiang Wang', 'bl-ue', 'Ruben Vereecken']
date: 1634674282
title: "unzip"
description: "unzip, Extract compressed files in a ZIP archive."
categories: "common"
---
> More information: <https://manned.org/unzip>.

- Extract zip file(s) (for multiple files, separate file paths by spaces):

```bash
unzip file(s)
```

- Extract zip files(s) to given path:

```bash
unzip compressed_file(s) -d path/to/put/extracted_file(s)
```

- List the contents of a zip file without extracting:

```bash
unzip -l file.zip
```

- Extract the contents of the file(s) to stdout alongside the extracted file names:

```bash
unzip -c file.zip
```

- Extract a zip file created on Windows, containing files with non-ASCII (e.g. Chinese or Japanese characters) filenames:

```bash
unzip -O gbk file.zip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Brian Choromanski](mailto:BrianChoromanski@gmail.com) | auditd, sftp, time, umount, unzip, w, which, wpa_supplicant: add link (#7037) | 2021-10-19T22:11:22 | [7f29e1695f3a](https://github.com/tldr-pages/tldr/commit/7f29e1695f3a3e3a2ecc20c730b8484a59daa588)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | unzip: clarify charset description | 2018-05-09T08:54:36 | [8f6a40fe9a0c](https://github.com/tldr-pages/tldr/commit/8f6a40fe9a0c15d33ae3ce0708cf6a555ec627c0)
[Xiang Wang](mailto:ramwin@qq.com) | unzip extract non-ascii file | 2018-05-09T08:54:36 | [0c45920e1fad](https://github.com/tldr-pages/tldr/commit/0c45920e1fad25d3f9c3651cd2a92eedc3791d33)
[WrathZA](mailto:miller.brettm@gmail.com) | unzip: include example of extracting to console. (#1705) | 2017-12-05T18:53:15 | [def44ed37fbf](https://github.com/tldr-pages/tldr/commit/def44ed37fbf0bbac96c7a3ccab818eac81854c6)
[Wolfgang Lutz](mailto:WLBORg@gmx.de) | fix typos using misspell (#1374) | 2017-05-12T11:29:18 | [550ede5cfb90](https://github.com/tldr-pages/tldr/commit/550ede5cfb90cb772d1ecf27241b22e5086b024b)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

