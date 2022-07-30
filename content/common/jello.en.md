---
author: ['Kelly Brazil']
date: 1623508203
title: "jello"
description: "jello, A command-line JSON processor using Python syntax."
categories: "common"
---
> More information: <https://github.com/kellyjonbrazil/jello>.

- Pretty-print JSON or JSON-Lines data from stdin to stdout:

```bash
cat file.json | jello
```

- Output a schema of JSON or JSON Lines data from stdin to stdout (useful for grep):

```bash
cat file.json | jello -s
```

- Output all elements from arrays (or all the values from objects) in JSON or JSON-Lines data from stdin to stdout:

```bash
cat file.json | jello -l
```

- Output the first element in JSON or JSON-Lines data from stdin to stdout:

```bash
cat file.json | jello _[0]
```

- Output the value of a given key of each element in JSON or JSON-Lines data from stdin to stdout:

```bash
cat file.json | jello '[i.key_name for i in _]'
```

- Output the value of multiple keys as a new JSON object (assuming the input JSON has the keys `key_name` and `other_key_name`):

```bash
cat file.json | jello '{"my_new_key": _.key_name, "my_other_key": _.other_key_name}'
```

- Output the value of a given key to a string (and disable JSON output):

```bash
cat file.json | jello -r '"some text: " + _.key_name'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kelly Brazil](mailto:kellyjonbrazil@gmail.com) | jello: add page (#6113) * jello: add page add page for jello command (I am the author) https://github.com/kellyjonbrazil/jello * add [...] | 2021-06-12T16:30:03 | [675c18582c4e](https://github.com/tldr-pages/tldr/commit/675c18582c4e892df92d2ad8ecebcc8bd8d8e669)

