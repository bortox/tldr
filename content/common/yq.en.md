---
author: ['Joshua Casey', 'Lucas Gabriel Schneider']
date: 1612112718
title: "yq, TLDR Pages"
description: "yq, A lightweight and portable command-line YAML processor."
categories: "common"
---
> More information: <https://mikefarah.gitbook.io/yq/>.

- Output a YAML file, in pretty-print format (v4+):

```bash
yq eval path/to/file.yaml
```

- Output a YAML file, in pretty-print format (v3):

```bash
yq read path/to/file.yaml --colors
```

- Output the first element in a YAML file that contains only an array (v4+):

```bash
yq eval '.[0]' path/to/file.yaml
```

- Output the first element in a YAML file that contains only an array (v3):

```bash
yq read path/to/file.yaml '[0]'
```

- Set (or overwrite) a key to a value in a file (v4+):

```bash
yq eval '.key = "value"' --inplace path/to/file.yaml
```

- Set (or overwrite) a key to a value in a file (v3):

```bash
yq write --inplace path/to/file.yaml 'key' 'value'
```

- Merge two files and print to stdout (v4+):

```bash
yq eval-all 'select(filename == "path/to/file1.yaml") * select(filename == "path/to/file2.yaml")' path/to/file1.yaml path/to/file2.yaml
```

- Merge two files and print to stdout (v3):

```bash
yq merge path/to/file1.yaml path/to/file2.yaml --colors
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Joshua Casey](mailto:joshuatcasey@gmail.com) | yq: add page (#5044) | 2021-01-04T18:59:15 | [f16f23ab8578](https://github.com/tldr-pages/tldr/commit/f16f23ab85786d865eb9bca6d1386889e0b88693)

