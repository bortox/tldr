---
author: ['Owen Voke', 'pxgamer']
date: 1559328460
title: "phpenv"
description: "phpenv, A PHP version manager for development purposes."
categories: "common"
---
> More information: <https://github.com/phpenv/phpenv>.

- Install a PHP version globally:

```bash
phpenv install version
```

- Refresh shim files for all PHP binaries known to `phpenv`:

```bash
phpenv rehash
```

- List all installed PHP versions:

```bash
phpenv versions
```

- Display the currently active PHP version:

```bash
phpenv version
```

- Set the global PHP version:

```bash
phpenv global version
```

- Set the local PHP version, which overrides the global version:

```bash
phpenv local version
```

- Unset the local PHP version:

```bash
phpenv local --unset
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | phpenv: add link to homepage | 2019-05-31T20:47:40 | [f2fb081987c3](https://github.com/tldr-pages/tldr/commit/f2fb081987c3a8800d55eb2883a69b9f39c42377)
[Owen Voke](mailto:owzie123@gmail.com) | phpenv: add page (#2721) | 2019-01-23T19:02:13 | [a0cbc90c3a35](https://github.com/tldr-pages/tldr/commit/a0cbc90c3a356e2fdb86bdae640d6272353b488b)

