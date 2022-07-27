---
author: ['pxgamer']
date: 1559676580
title: "magento, TLDR Pages"
description: "magento, A CLI for managing the Magento PHP framework."
categories: "common"
---
> More information: <https://magento.com>.

- Enable one or more space-separated modules:

```bash
magento module:enable module(s)
```

- Disable one or more space-separated modules:

```bash
magento module:disable module(s)
```

- Update the database after enabling modules:

```bash
magento setup:upgrade
```

- Update code and dependency injection configuration:

```bash
magento setup:di:compile
```

- Deploy static assets:

```bash
magento setup:static-content:deploy
```

- Enable maintenance mode:

```bash
magento maintenance:enable
```

- Disable maintenance mode:

```bash
magento maintenance:disable
```

- List all available commands:

```bash
magento list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | magento: add link to homepage | 2019-06-04T21:29:40 | [70c6287c8c1f](https://github.com/tldr-pages/tldr/commit/70c6287c8c1f1c8c144b35d1f3188b14a1cfe889)
[pxgamer](mailto:owzie123@gmail.com) | magento: change to 'deploy static assets' | 2018-06-06T07:12:29 | [a36a3c6358ad](https://github.com/tldr-pages/tldr/commit/a36a3c6358ad1a98cdaaffaf21e6c3d266f2d417)
[pxgamer](mailto:owzie123@gmail.com) | magento: move db upgrade below module examples | 2018-06-06T07:12:29 | [bc8b879caf16](https://github.com/tldr-pages/tldr/commit/bc8b879caf16dba92bcc09d35144e7a788904119)
[pxgamer](mailto:owzie123@gmail.com) | magento: add additional command examples | 2018-06-06T07:12:29 | [a14c47535a51](https://github.com/tldr-pages/tldr/commit/a14c47535a51d5a6e4ca5e88d5d676a4f6c8a769)
[pxgamer](mailto:owzie123@gmail.com) | magento: add page | 2018-06-06T07:12:29 | [54ab80bef10f](https://github.com/tldr-pages/tldr/commit/54ab80bef10fb23b4c5a37c25f0126411186b008)

