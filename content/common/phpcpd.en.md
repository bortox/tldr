---
author: ['Owen Voke', 'pxgamer', 'Seth Falco']
date: 1656325392
title: "phpcpd"
description: "phpcpd, A copy and paste detector for PHP code."
categories: "common"
---
> More information: <https://github.com/sebastianbergmann/phpcpd>.

- Analyze duplicated code for a specific file or directory:

```bash
phpcpd path/to/file_or_directory
```

- Analyze using fuzzy matching for variable names:

```bash
phpcpd --fuzzy path/to/file_or_directory
```

- Specify a minimum number of identical lines (defaults to 5):

```bash
phpcpd --min-lines number_of_lines path/to/file_or_directory
```

- Specify a minimum number of identical tokens (defaults to 70):

```bash
phpcpd --min-tokens number_of_tokens path/to/file_or_directory
```

- Exclude a directory from analysis (must be relative to the source):

```bash
phpcpd --exclude path/to/excluded_directory path/to/file_or_directory
```

- Output the results to a PHP-CPD XML file:

```bash
phpcpd --log-pmd path/to/log_file path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[pxgamer](mailto:owzie123@gmail.com) | phpcpd: add link to homepage | 2019-05-31T20:47:40 | [b7ba66a63e60](https://github.com/tldr-pages/tldr/commit/b7ba66a63e608e56da79614e9ed5843f32d6abd3)
[Owen Voke](mailto:owzie123@gmail.com) | phpcpd: add page (#2614) | 2018-11-26T19:10:58 | [bb06748ab39c](https://github.com/tldr-pages/tldr/commit/bb06748ab39c1afa35bab7770283875834255e98)

