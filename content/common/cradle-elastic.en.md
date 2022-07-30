---
author: ['pxgamer', 'Seth Falco']
date: 1629050349
title: "cradle elastic"
description: "cradle elastic, Manage the Elasticsearch instances for a Cradle instance."
categories: "common"
---
> More information: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#elastic>.

- Truncate the Elasticsearch index:

```bash
cradle elastic flush
```

- Truncate the Elasticsearch index for a specific package:

```bash
cradle elastic flush package_name
```

- Submit the Elasticsearch schema:

```bash
cradle elastic map
```

- Submit the Elasticsearch schema for a specific package:

```bash
cradle elastic map package_name
```

- Populate the Elasticsearch indices for all packages:

```bash
cradle elastic populate
```

- Populate the Elasticsearch indices for a specific package:

```bash
cradle elastic populate package_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | cradle-elastic: add link to homepage | 2019-06-09T18:53:49 | [00537dfd2cb4](https://github.com/tldr-pages/tldr/commit/00537dfd2cb465e77e2f2fc99b10152601360f38)
[pxgamer](mailto:owzie123@gmail.com) | cradle-elastic: update indexes to indices | 2018-11-14T12:51:07 | [59d31084d246](https://github.com/tldr-pages/tldr/commit/59d31084d2461b105a97444398f07cf04884b06b)
[pxgamer](mailto:owzie123@gmail.com) | cradle-elastic: update token wording | 2018-11-14T12:51:07 | [72f5216f6c0c](https://github.com/tldr-pages/tldr/commit/72f5216f6c0c51ad91e523841b392b93ecc55cfc)
[pxgamer](mailto:owzie123@gmail.com) | cradle-elastic: make the description more clear | 2018-11-14T12:51:07 | [744acae9720a](https://github.com/tldr-pages/tldr/commit/744acae9720a1a70a45764a675484f2964b10af6)
[pxgamer](mailto:owzie123@gmail.com) | cradle-elastic: add page | 2018-11-14T12:51:07 | [b81d2a4c7c9b](https://github.com/tldr-pages/tldr/commit/b81d2a4c7c9b7909726b06b7cefc659a1f388e2d)

