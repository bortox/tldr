---
author: ['Owen Voke', 'bl-ue']
date: 1612669725
title: "php-coveralls"
description: "php-coveralls, A PHP client for Coveralls."
categories: "common"
---
> More information: <https://php-coveralls.github.io/php-coveralls>.

- Send coverage information to Coveralls:

```bash
php-coveralls
```

- Send coverage information to Coveralls for a specific directory:

```bash
php-coveralls --root_dir path/to/directory
```

- Send coverage information to Coveralls with a specific config:

```bash
php-coveralls --config path/to/.coveralls.yml
```

- Send coverage information to Coveralls with verbose output:

```bash
php-coveralls --verbose
```

- Send coverage information to Coveralls excluding source files with no executable statements:

```bash
php-coveralls --exclude-no-stmt
```

- Send coverage information to Coveralls with a specific environment name:

```bash
php-coveralls --env test|dev|prod
```

- Specify multiple Coverage Clover XML files to upload:

```bash
php-coveralls --coverage_clover path/to/first_clover.xml --coverage_clover path/to/second_clover.xml
```

- Output the JSON that will be sent to Coveralls to a specific file:

```bash
php-coveralls --json_path path/to/coveralls-upload.json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | conan, php-coveralls: fix typos (#5253) | 2021-02-07T04:48:45 | [a810ca72d7aa](https://github.com/tldr-pages/tldr/commit/a810ca72d7aa01cd5b9093d4b208b23c5b2982e0)
[Owen Voke](mailto:development@voke.dev) | php-coveralls: add page (#5235) | 2021-02-05T14:53:51 | [cae5a927a849](https://github.com/tldr-pages/tldr/commit/cae5a927a84901432bb93a744bd22b9da23c223c)

