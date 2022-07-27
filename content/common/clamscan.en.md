---
author: ['Waldir Pimenta', 'Owen Voke', 'Marco Bonelli', 'Lucas Gabriel Schneider', 'bl-ue']
date: 1621541621
title: "clamscan, TLDR Pages"
description: "clamscan, A command-line virus scanner."
categories: "common"
---
> More information: <https://www.clamav.net>.

- Scan a file for vulnerabilities:

```bash
clamscan path/to/file
```

- Scan all files recursively in a specific directory:

```bash
clamscan -r path/to/directory
```

- Scan data from stdin:

```bash
command | clamscan -
```

- Specify a virus database file or directory of files:

```bash
clamscan --database path/to/database_file_or_directory
```

- Scan the current directory and output only infected files:

```bash
clamscan --infected
```

- Output the scan report to a log file:

```bash
clamscan --log path/to/log_file
```

- Move infected files to a specific directory:

```bash
clamscan --move path/to/quarantine_directory
```

- Remove infected files:

```bash
clamscan --remove yes
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | clamscan: add page (#2815) | 2019-03-05T01:11:21 | [32ffc76159b0](https://github.com/tldr-pages/tldr/commit/32ffc76159b08391455083ec496a329f751b140f)

