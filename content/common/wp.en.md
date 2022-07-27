---
author: ['iSnackyCracky', 'Seth']
date: 1630843924
title: "wp, TLDR Pages"
description: "wp, The official command-line interface to manage WordPress instances."
categories: "common"
---
> More information: <https://wp-cli.org/>.

- Print information about the operating system, shell, PHP, and WP-CLI (`wp`) installation:

```bash
wp --info
```

- Update WP-CLI:

```bash
wp cli update
```

- Download a fresh WordPress installation to current directory, optionally specifying the locale:

```bash
wp core download --locale=locale
```

- Create basic `wpconfig` file (assuming database on `localhost`):

```bash
wp config create --dbname=dbname --dbuser=dbuser --dbpass=dbpass
```

- Install and activate a WordPress plugin:

```bash
wp plugin install plugin --activate
```

- Replace all instances of a string in the database:

```bash
wp search-replace old_string new_string
```

- Import the contents of a WordPress Extended RSS (WXR) file:

```bash
wp import path/to/file.xml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[iSnackyCracky](mailto:julian@isnackycracky.de) | wp: add download and config examples (#6461) | 2021-09-05T14:12:04 | [70093834fdcc](https://github.com/tldr-pages/tldr/commit/70093834fdcc07cfc72d9a56e660475d5e3bcf93)
[Seth](mailto:seth@falco.fun) | wp: add page (#5985) | 2021-05-18T20:30:58 | [7b1de0b54fca](https://github.com/tldr-pages/tldr/commit/7b1de0b54fcafc3dd63bcf8ceded088e9f6d992c)

