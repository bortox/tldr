---
author: ['B. Mearns']
date: 1602527810
title: "aws kinesis, TLDR Pages"
description: "aws kinesis, Official AWS CLI for Amazon Kinesis streaming data services."
categories: "common"
---
> More information: <https://docs.aws.amazon.com/cli/latest/reference/kinesis/index.html#cli-aws-kinesis>.

- Show all streams in the account:

```bash
aws kinesis list-streams
```

- Write one record to a Kinesis stream:

```bash
aws kinesis put-record --stream-name name --partition-key key --data base64_encoded_message
```

- Write a record to a Kinesis stream with inline base64 encoding:

```bash
aws kinesis put-record --stream-name name --partition-key key --data "$( echo "my raw message" | base64 )"
```

- List the shards available on a stream:

```bash
aws kinesis list-shards --stream-name name
```

- Get a shard iterator for reading from the oldest message in a stream's shard:

```bash
aws kinesis get-shard-iterator --shard-iterator-type TRIM_HORIZON --stream-name name --shard-id id
```

- Read records from a shard, using a shard iterator:

```bash
aws kinesis get-records --shard-iterator iterator
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[B. Mearns](mailto:mearns@users.noreply.github.com) | aws-kinesis: add page (#4510) | 2020-10-12T20:36:50 | [7fcea618b710](https://github.com/tldr-pages/tldr/commit/7fcea618b7109e9a5db84a17cf9a0ece2383ce79)

