---
author: ['Dina Basumatary']
date: 1649326981
title: "bq"
description: "bq, The bq command-line tool is a Python-based command-line tool for BigQuery."
categories: "common"
---
> More information: <https://cloud.google.com/bigquery/docs/reference/bq-cli-reference>.

- Run query against a BigQuery table using standard SQL, add `--dry_run` flag to estimate the number of bytes read by the query:

```bash
bq query --nouse_legacy_sql 'SELECT COUNT(*) FROM DATASET_NAME.TABLE_NAME'
```

- Run a parameterized query:

```bash
bq query --use_legacy_sql=false --parameter='ts_value:TIMESTAMP:2016-12-07 08:00:00' 'SELECT TIMESTAMP_ADD(@ts_value, INTERVAL 1 HOUR)'
```

- Create a new dataset or table in the US location:

```bash
bq mk --location=US dataset_name.table_name
```

- List all datasets in a project:

```bash
bq ls --filter labels.key:value --max_results integer --format=prettyjson --project_id project_id
```

- Batch load data from a specific file in formats such as CSV, JSON, Parquet, and Avro to a table:

```bash
bq load --location=location --source_format=CSV|JSON|PARQUET|AVRO dataset.table path_to_source
```

- Copy one table to another:

```bash
bq cp dataset.OLD_TABLE dataset.new_table
```

- Print help:

```bash
bq help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dina Basumatary](mailto:dnafication@users.noreply.github.com) | bq: add page (#7962) * gsutil: add page * bq: add page * Revert "gsutil: add page" This reverts commit [...] | 2022-04-07T12:23:01 | [95024e845100](https://github.com/tldr-pages/tldr/commit/95024e845100e7c5ea380ace08f3060e12737d49)

