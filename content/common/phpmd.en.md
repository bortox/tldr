---
author: ['Waldir Pimenta', 'Lucas Gabriel Schneider', 'pxgamer']
date: 1612112718
title: "phpmd, TLDR Pages"
description: "phpmd, A PHP mess detector that checks for common potential problems."
categories: "common"
---
> More information: <https://github.com/phpmd/phpmd>.

- Display a list of available rulesets and formats:

```bash
phpmd
```

- Scan a file or directory for problems using comma-separated rulesets:

```bash
phpmd path/to/file_or_directory xml|text|html rulesets
```

- Specify the minimum priority threshold for rules:

```bash
phpmd path/to/file_or_directory xml|text|html rulesets --minimumpriority priority
```

- Include only the specified extensions in analysis:

```bash
phpmd path/to/file_or_directory xml|text|html rulesets --suffixes extensions
```

- Exclude the specified comma-separated directories:

```bash
phpmd path/to/file_or_directory xml|text|html rulesets --exclude directory_patterns
```

- Output the results to a file instead of stdout:

```bash
phpmd path/to/file_or_directory xml|text|html rulesets --reportfile path/to/report_file
```

- Ignore the use of warning-suppressive PHPDoc comments:

```bash
phpmd path/to/file_or_directory xml|text|html rulesets --strict
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | phpmd: add link to homepage | 2019-05-31T20:47:40 | [ee0c40c56393](https://github.com/tldr-pages/tldr/commit/ee0c40c5639311c910116406adb79c0d6bda3e7e)
[pxgamer](mailto:owzie123@gmail.com) | phpmd: update warning suppression wording | 2018-12-12T15:54:05 | [903e198cedff](https://github.com/tldr-pages/tldr/commit/903e198cedff622ffb145bb09671eb1a5f667fef)
[pxgamer](mailto:owzie123@gmail.com) | phpmd: add page | 2018-12-12T15:54:05 | [c59f83ba271c](https://github.com/tldr-pages/tldr/commit/c59f83ba271ce5fe84e96ce2843f57e4881e9edb)

