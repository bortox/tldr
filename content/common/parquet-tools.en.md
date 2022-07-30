---
author: ['ktrueda', 'marchersimon']
date: 1625253777
title: "parquet-tools"
description: "parquet-tools, A tool to show, inspect and manipulate Parquet file."
categories: "common"
---
> More information: <https://github.com/apache/parquet-mr/tree/master/parquet-tools-deprecated>.

- Display the content of a Parquet file:

```bash
parquet-tools cat path/to/parquet
```

- Display the first few lines of a Parquet file:

```bash
parquet-tools head path/to/parquet
```

- Print the schema of a Parquet file:

```bash
parquet-tools schema path/to/parquet
```

- Print the metadata of a Parquet file:

```bash
parquet-tools meta path/to/parquet
```

- Print the content and metadata of a Parquet file:

```bash
parquet-tools dump path/to/parquet
```

- Concatenate several Parquet files into the target one:

```bash
parquet-tools merge path/to/parquet1 path/to/parquet2 path/to/target_parquet
```

- Print the count of rows in a Parquet file:

```bash
parquet-tools rowcount path/to/parquet
```

- Print the column and offset indexes of a Parquet file:

```bash
parquet-tools column-index path/to/parquet
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[ktrueda](mailto:ktrueda@users.noreply.github.com) | parquet-tools: add page (#4588) | 2020-10-10T17:45:08 | [be0e6cb27216](https://github.com/tldr-pages/tldr/commit/be0e6cb27216c92f22ab55812772247c670629ee)

