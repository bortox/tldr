---
author: ['258204']
date: 1624458712
title: "aws s3api, TLDR Pages"
description: "aws s3api, Create and delete Amazon S3 buckets and edit bucket properties."
categories: "common"
---
> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3api/index.html>.

- Create a bucket:

```bash
aws s3api create-bucket --bucket bucket_name
```

- Delete a bucket:

```bash
aws s3api delete-bucket --bucket bucket_name
```

- List buckets:

```bash
aws s3api list-buckets
```

- List the objects inside of a bucket and only show each object's key and size:

```bash
aws s3api list-objects --bucket bucket_name --query 'Contents[].{Key: Key, Size: Size}'
```

- Add an object to a bucket:

```bash
aws s3api put-object --bucket bucket_name --key object_key --body path/to/file
```

- Download object from a bucket (The output file is always the last argument):

```bash
aws s3api get-object --bucket bucket_name --key object_key path/to/output_file
```

- Apply an Amazon S3 bucket policy to a specified bucket:

```bash
aws s3api put-bucket-policy --bucket bucket_name --policy file://path/to/bucket_policy.json
```

- Download the Amazon S3 bucket policy from a specified bucket:

```bash
aws s3api get-bucket-policy --bucket bucket_name --query Policy --output json|table|text|yaml|yaml-stream > path/to/bucket_policy
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[258204](mailto:71364336+258204@users.noreply.github.com) | aws-s3api: add page (#6132) | 2021-06-23T16:31:52 | [a01df47bc1a2](https://github.com/tldr-pages/tldr/commit/a01df47bc1a2ac9b568cd3707317795b84bc1d5a)

