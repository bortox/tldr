---
author: ['Jonatas Leon', 'marchersimon']
date: 1618584134
title: "lftp, TLDR Pages"
description: "lftp, Sophisticated file transfer program."
categories: "linux"
---
> More information: <https://lftp.yar.ru/lftp-man.html>.

- Connect to an FTP server:

```bash
lftp ftp.example.com
```

- Download multiple files (glob expression):

```bash
mget path/to/*.png
```

- Upload multiple files (glob expression):

```bash
mput path/to/*.zip
```

- Delete multiple files on the remote server:

```bash
mrm path/to/*.txt
```

- Rename a file on the remote server:

```bash
mv original_filename new_filename
```

- Download or update an entire directory:

```bash
mirror path/to/remote_dir path/to/local_output_dir
```

- Upload or update an entire directory:

```bash
mirror -R path/to/local_dir path/to/remote_output_dir
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Jonatas Leon](mailto:jonatas.leon@gmail.com) | lftp: add page (#4157) Co-authored-by: Ein Verne <git@einverne.info> Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-07-12T15:59:45 | [efd81478f177](https://github.com/tldr-pages/tldr/commit/efd81478f1773143fc3fa8e575b681ccf393978e)

