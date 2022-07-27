---
author: ['Pierre Rudloff', 'Sarah Haïm-Lubczanski', 'Seth Falco']
date: 1635871374
title: "phpenmod, TLDR Pages"
description: "phpenmod, Enable PHP extensions on Debian-based OSes."
categories: "linux"
---
> More information: <https://salsa.debian.org/php-team/php-defaults>.

- Enable the JSON extension for every SAPI of every PHP version:

```bash
sudo phpenmod json
```

- Enable the JSON extension for PHP 7.3 with the cli SAPI:

```bash
sudo phpenmod -v 7.3 -s cli json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sarah Haïm-Lubczanski](mailto:205895+mere-teresa@users.noreply.github.com) | phpenmod: add more information link (#7324) | 2021-11-02T17:42:54 | [7df608099c0b](https://github.com/tldr-pages/tldr/commit/7df608099c0b4a80a25965d7ecfa4dc545c5c6cd)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Pierre Rudloff](mailto:contact@rudloff.pro) | phpdismod, phpenmod, phpquery: add page (#3610) | 2019-11-26T19:59:16 | [293d698b85ea](https://github.com/tldr-pages/tldr/commit/293d698b85eabf05ba408223d92bee1bf7250eb0)

