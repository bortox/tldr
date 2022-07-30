---
author: ['Nicolas Kosinski']
date: 1618083945
title: "fakedata"
description: "fakedata, Generate fake data using a large variety of generators."
categories: "common"
---
> More information: <https://github.com/lucapette/fakedata>.

- List all valid generators:

```bash
fakedata --generators
```

- Generate data using one or more generators:

```bash
fakedata generator1 generator2
```

- Generate data with a specific output format:

```bash
fakedata --format csv|tab|sql generator
```

- Generate a given number of data items (defaults to 10):

```bash
fakedata --limit n generator
```

- Generate data using a custom output template (the first letter of generator names must be capitalized):

```bash
echo "\{\{Generator\}\}" | fakedata
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | fakedata: add page (#5675) | 2021-04-10T21:45:45 | [6b14fd4ec918](https://github.com/tldr-pages/tldr/commit/6b14fd4ec9180e319dffc56ea189e75898515ed0)

