---
author: ['Alex']
date: 1585590807
title: "dirsearch"
description: "dirsearch, Web path scanner."
categories: "common"
---
> More information: <https://github.com/maurosoria/dirsearch>.

- Scan a web server for common paths with common extensions:

```bash
dirsearch --url url --extensions-list
```

- Scan a list of web servers for common paths with the `.php` extension:

```bash
dirsearch --url-list path/to/url-list.txt --extensions php
```

- Scan a web server for user-defined paths with common extensions:

```bash
dirsearch --url url --extensions-list --wordlist path/to/url-paths.txt
```

- Scan a web server using a cookie:

```bash
dirsearch --url url --extensions php --cookie cookie
```

- Scan a web server using the `HEAD` HTTP method:

```bash
dirsearch --url url --extensions php --http-method HEAD
```

- Scan a web server, saving the results to a `.json` file:

```bash
dirsearch --url url --extensions php --json-report path/to/report.json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alex](mailto:alexandre.dhondt@gmail.com) | dirsearch: add page (#3949) | 2020-03-30T19:53:27 | [52edacb27d8b](https://github.com/tldr-pages/tldr/commit/52edacb27d8b6a692673d2c51a042639a1daf9dc)

