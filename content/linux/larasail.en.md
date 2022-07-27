---
author: ['Marco Bonelli', 'Owen Voke']
date: 1559564381
title: "larasail, TLDR Pages"
description: "larasail, A CLI tool for managing Laravel on Digital Ocean servers."
categories: "linux"
---
> More information: <https://github.com/thedevdojo/larasail>.

- Set up the server with Laravel dependencies using the default PHP version:

```bash
larasail setup
```

- Set up the server with Laravel dependencies using a specific PHP version:

```bash
larasail setup php71
```

- Add a new Laravel site:

```bash
larasail host domain path/to/site_directory
```

- Retrieve the Larasail user password:

```bash
larasail pass
```

- Retrieve the Larasail MySQL password:

```bash
larasail mysqlpass
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | larasail: add page (#2848) | 2019-03-26T02:56:05 | [fa21dc0a079d](https://github.com/tldr-pages/tldr/commit/fa21dc0a079d205d9b3c3b900e7dd60c2c976cb4)

