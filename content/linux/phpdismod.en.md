---
author: ['Sarah Haïm-Lubczanski', 'Pierre Rudloff', 'Seth Falco']
date: 1635871351
title: "phpdismod"
description: "phpdismod, Disable PHP extensions on Debian-based OSes."
categories: "linux"
---
> More information: <https://salsa.debian.org/php-team/php-defaults>.

- Disable the JSON extension for every SAPI of every PHP version:

```bash
sudo phpdismod json
```

- Disable the JSON extension for PHP 7.3 with the cli SAPI:

```bash
sudo phpdismod -v 7.3 -s cli json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sarah Haïm-Lubczanski](mailto:205895+mere-teresa@users.noreply.github.com) | phpdismod: add more information link (#7323) | 2021-11-02T17:42:31 | [ee6cdaaadf7e](https://github.com/tldr-pages/tldr/commit/ee6cdaaadf7ec93b9fc4d1ebd9e8185c04b8f0eb)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Pierre Rudloff](mailto:contact@rudloff.pro) | phpdismod, phpenmod, phpquery: add page (#3610) | 2019-11-26T19:59:16 | [293d698b85ea](https://github.com/tldr-pages/tldr/commit/293d698b85eabf05ba408223d92bee1bf7250eb0)

