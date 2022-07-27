---
author: ['Axel Navarro']
date: 1622380800
title: "mongoimport, TLDR Pages"
description: "mongoimport, Imports content from a JSON, CSV, or TSV file into a MongoDB database."
categories: "common"
---
> More information: <https://docs.mongodb.com/database-tools/mongoimport/>.

- Import a JSON file into a specific collection:

```bash
mongoimport --file=path/to/file.json --uri=mongodb_uri --collection=collection_name
```

- Import a CSV file, using the first line of the file to determine field names:

```bash
mongoimport --type=csv --file=path/to/file.csv --db=database_name --collection=collection_name
```

- Import a JSON array, using each element as a separate document:

```bash
mongoimport --jsonArray --file=path/to/file.json
```

- Import a JSON file using a specific mode and a query to match existing documents:

```bash
mongoimport --file=path/to/file.json --mode=delete|merge|upsert --upsertFields="field1,field2,..."
```

- Import a CSV file, reading field names from a separate CSV file and ignoring fields with empty values:

```bash
mongoimport --type=csv --file=path/to/file.csv --fieldFile=path/to/field_file.csv --ignoreBlanks
```

- Display help:

```bash
mongoimport --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | mongoimport: add page (#6008) | 2021-05-30T15:20:00 | [df2ebc7b862a](https://github.com/tldr-pages/tldr/commit/df2ebc7b862a8b85e661cbf845c9ae4f870b91f7)

