---
author: ['codesoap', 'sebastientinel', 'Juri']
date: 1634444636
title: "pax"
description: "pax, Archiving and copying utility."
categories: "common"
---
> More information: <https://manned.org/pax.1p>.

- List the contents of an archive:

```bash
pax -f archive.tar
```

- List the contents of a gzipped archive:

```bash
pax -zf archive.tar.gz
```

- Create an archive from files:

```bash
pax -wf target.tar path/to/file1 path/to/file2 path/to/file3
```

- Create an archive from files, using output redirection:

```bash
pax -w path/to/file1 path/to/file2 path/to/file3 > target.tar
```

- Extract an archive into the current directory:

```bash
pax -rf source.tar
```

- Copy to a directory, while keeping the original metadata; `target/` must exist:

```bash
pax -rw path/to/file1 path/to/directory1 path/to/directory2 target/
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | meshlabserver, nkf, obs, pax, pdfimages, pinky, pssh, s, sd, sendmail, sftp: add link (#6971) | 2021-10-17T06:23:56 | [977d4212d52c](https://github.com/tldr-pages/tldr/commit/977d4212d52c031de053f549d819b8b0e18ce184)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[codesoap](mailto:42150522+codesoap@users.noreply.github.com) | pax: add page (#2870) | 2019-04-06T14:40:26 | [5b040615719f](https://github.com/tldr-pages/tldr/commit/5b040615719fd6163d7c32479096a88bf21662ca)

