---
author: ['Stepan Pyzhov']
date: 1595007804
title: "ajson, TLDR Pages"
description: "ajson, Executes JSONPath on JSON objects."
categories: "common"
---
> More information: <https://github.com/spyzhov/ajson>.

- Read JSON from a file and execute a specified JSONPath expression:

```bash
ajson '$..json[?(@.path)]' path/to/file.json
```

- Read JSON from stdin and execute a specified JSONPath expression:

```bash
cat path/to/file.json | ajson '$..json[?(@.path)]'
```

- Read JSON from a URL and evaluate a specified JSONPath expression:

```bash
ajson 'avg($..price)' 'https://example.com/api/'
```

- Read some simple JSON and calculate a value:

```bash
echo '3' | ajson '2 * pi * $'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stepan Pyzhov](mailto:32341341+spyzhov@users.noreply.github.com) | ajson: add page (#4191) | 2020-07-17T19:43:24 | [3cff0e39145d](https://github.com/tldr-pages/tldr/commit/3cff0e39145da3cc84c11fba6e03c22448520b7f)

