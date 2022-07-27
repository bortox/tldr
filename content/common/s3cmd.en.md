---
author: ['Bjørn Gustav Baklid']
date: 1657430375
title: "s3cmd, TLDR Pages"
description: "s3cmd, Command line tool and client for uploading, retrieveing and managing data in S3 compatible object storage."
categories: "common"
---
> More information: <https://s3tools.org/s3cmd>.

- Invoke configuration/reconfiguration tool:

```bash
s3cmd --configure
```

- List Buckets/Folders/Objects:

```bash
s3cmd ls s3://bucket|path/to/file
```

- Create Bucket/Folder:

```bash
s3cmd mb s3://bucket
```

- Download a specific file from a bucket:

```bash
s3cmd get s3://bucket_name/path/to/file path/to/local_file
```

- Upload a file to a bucket:

```bash
s3cmd put local_file s3://bucket/file
```

- Move an object to a specific bucket location:

```bash
s3cmd mv s3://src_bucket/src_object s3://dst_bucket/dst_object
```

- Delete a specific object:

```bash
s3cmd rm s3://bucket/object
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bjørn Gustav Baklid](mailto:bg@dyret.net) | s3cmd: add page (#8074) | 2022-07-10T07:19:35 | [8f76214518c9](https://github.com/tldr-pages/tldr/commit/8f76214518c9b7de62bcbeab948c6d586b9c6c45)

