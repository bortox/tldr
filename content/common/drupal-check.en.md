---
author: ['Pierre Rudloff']
date: 1601909719
title: "drupal-check"
description: "drupal-check, Check Drupal PHP code for deprecations."
categories: "common"
---
> More information: <https://github.com/mglaman/drupal-check>.

- Check the code in a specific directory for deprecations:

```bash
drupal-check path/to/directory
```

- Check the code excluding a comma-separated list of directories:

```bash
drupal-check --exclude-dir path/to/excluded_directory,path/to/excluded_files/*.php path/to/directory
```

- Don't show a progress bar:

```bash
drupal-check --no-progress path/to/directory
```

- Perform static analysis to detect bad coding practices:

```bash
drupal-check --analysis path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:50333926+prudloff-insite@users.noreply.github.com) | drupal-check: add page (#4410) | 2020-10-05T16:55:19 | [02f68ba74a44](https://github.com/tldr-pages/tldr/commit/02f68ba74a445f2f5181670efe4041ae1a87b63a)

