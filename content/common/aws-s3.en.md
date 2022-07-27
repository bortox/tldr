---
author: ['Marco Bonelli', 'pxgamer', 'syleung', 'Daniel Choudhury']
date: 1633113644
title: "aws s3, TLDR Pages"
description: "aws s3, CLI for AWS S3 - provides storage through web services interfaces."
categories: "common"
---
> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3/index.html>.

- Show files in a bucket:

```bash
aws s3 ls bucket_name
```

- Sync files and directories from local to bucket:

```bash
aws s3 sync path/to/files s3://bucket_name
```

- Sync files and directories from bucket to local:

```bash
aws s3 sync s3://bucket_name path/to/target
```

- Sync files and directories with exclusions:

```bash
aws s3 sync path/to/files s3://bucket_name --exclude path/to/file --exclude path/to/directory/*
```

- Remove file from bucket:

```bash
aws s3 rm s3://bucket/path/to/file
```

- Preview changes only:

```bash
aws s3 any_command --dryrun
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | aws-s3: fix more information link (#6642) | 2021-10-01T20:40:44 | [0503024ae33c](https://github.com/tldr-pages/tldr/commit/0503024ae33cc4058e96b3fd915fbe2b80572bc2)
[pxgamer](mailto:owzie123@gmail.com) | aws-s3: add link to homepage | 2019-06-09T18:53:49 | [88fd2c5bdece](https://github.com/tldr-pages/tldr/commit/88fd2c5bdece755be5879060fe537e83414483c1)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Daniel Choudhury](mailto:dannychoudhury@gmail.com) | Made requested changes, remove bucket to bucket sync example | 2016-11-19T18:12:14 | [911521fc4553](https://github.com/tldr-pages/tldr/commit/911521fc4553cd6392909f768b15344c9506dcf3)
[Daniel Choudhury](mailto:dannychoudhury@gmail.com) | Adding aws s3 cheatsheet | 2016-11-19T18:12:14 | [b6002b0606f5](https://github.com/tldr-pages/tldr/commit/b6002b0606f50ed0ed5cb79bd3076523bc5aef62)

