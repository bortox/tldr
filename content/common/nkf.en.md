---
author: ['Juri', 'Seth Falco', 'pr0xy']
date: 1634444636
title: "nkf"
description: "nkf, Network kanji filter."
categories: "common"
---
> Converts kanji code from one encoding to another.

> More information: <https://manned.org/nkf>.

- Convert to UTF-8 encoding:

```bash
nkf -w path/to/file.txt
```

- Convert to SHIFT_JIS encoding:

```bash
nkf -s path/to/file.txt
```

- Convert to UTF-8 encoding and overwrite the file:

```bash
nkf -w --overwrite path/to/file.txt
```

- Set new line code to LF and overwrite (UNIX type):

```bash
nkf -d --overwrite path/to/file.txt
```

- Set new line code to CRLF and overwrite (windows type):

```bash
nkf -c --overwrite path/to/file.txt
```

- Decrypt mime file and overwrite:

```bash
nkf -m --overwrite path/to/file.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | meshlabserver, nkf, obs, pax, pdfimages, pinky, pssh, s, sd, sendmail, sftp: add link (#6971) | 2021-10-17T06:23:56 | [977d4212d52c](https://github.com/tldr-pages/tldr/commit/977d4212d52c031de053f549d819b8b0e18ce184)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pr0xy](mailto:42575435+pr0xy-t@users.noreply.github.com) | nkf: add page (#2795) | 2019-12-15T06:03:00 | [3295981a7224](https://github.com/tldr-pages/tldr/commit/3295981a722453c95d639e1ef601c1bea513606f)

