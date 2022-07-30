---
author: ['Axel Navarro']
date: 1625129244
title: "mongoexport"
description: "mongoexport, Produce exports of data stored in a MongoDB instance formatted as JSON or CSV."
categories: "common"
---
> More information: <https://docs.mongodb.com/database-tools/mongoexport/>.

- Export a collection to stdout, formatted as JSON:

```bash
mongoexport --uri=connection_string --collection=collection_name
```

- Export the documents in the specified collection that match a query to a JSON file:

```bash
mongoexport --db=database_name --collection=collection_name --query="query_object" --out=path/to/file.json
```

- Export documents as a JSON array instead of one object per line:

```bash
mongoexport --collection=collection_name --jsonArray
```

- Export documents to a CSV file:

```bash
mongoexport --collection=collection_name --type=csv --fields="field1,field2,..." --out=path/to/file.csv
```

- Export documents that match the query in the specified file to a CSV file, omitting the list of field names on the first line:

```bash
mongoexport --collection=collection_name --type=csv --fields="field1,field2,..." --queryFile=path/to/file --noHeaderLine --out=path/to/file.csv
```

- Export documents to stdout, formatted as human-readable JSON:

```bash
mongoexport --uri=mongodb_uri --collection=collection_name --pretty
```

- Display help:

```bash
mongoexport --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | mongoexport: add page (#6041) | 2021-07-01T10:47:24 | [b082abb50f0e](https://github.com/tldr-pages/tldr/commit/b082abb50f0e6ea12343e00b9b69f767f82da5bc)

