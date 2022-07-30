---
author: ['Pierre Rudloff', 'Emily Grace Seville', 'Seth Falco']
date: 1647882468
title: "phpquery"
description: "phpquery, PHP extension manager for Debian-based OSes."
categories: "linux"
---
> More information: <https://helpmanual.io/help/phpquery/>.

- List available PHP versions:

```bash
sudo phpquery -V
```

- List available SAPIs for PHP 7.3:

```bash
sudo phpquery -v 7.3 -S
```

- List enabled extensions for PHP 7.3 with the cli SAPI:

```bash
sudo phpquery -v 7.3 -s cli -M
```

- Check if the JSON extension is enabled for PHP 7.3 with the apache2 SAPI:

```bash
sudo phpquery -v 7.3 -s apache2 -m json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Pierre Rudloff](mailto:contact@rudloff.pro) | phpdismod, phpenmod, phpquery: add page (#3610) | 2019-11-26T19:59:16 | [293d698b85ea](https://github.com/tldr-pages/tldr/commit/293d698b85eabf05ba408223d92bee1bf7250eb0)

