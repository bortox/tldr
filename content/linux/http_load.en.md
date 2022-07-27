---
author: ['XING YAHAO', 'Seth Falco']
date: 1629050349
title: "http_load, TLDR Pages"
description: "http_load, An HTTP benchmarking tool."
categories: "linux"
---
> Runs multiple HTTP fetches in parallel to test the throughput of a web server.

> More information: <http://www.acme.com/software/http_load/>.

- Emulate 20 requests based on a given URL list file per second for 60 seconds:

```bash
http_load -rate 20 -seconds 60 path/to/urls.txt
```

- Emulate 5 concurrent requests based on a given URL list file for 60 seconds:

```bash
http_load -parallel 5 -seconds 60 path/to/urls.txt
```

- Emulate 1000 requests at 20 requests per second, based on a given URL list file:

```bash
http_load -rate 20 -fetches 1000 path/to/urls.txt
```

- Emulate 1000 requests at 5 concurrent requests at a time, based on a given URL list file:

```bash
http_load -parallel 5 -fetches 1000 path/to/urls.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[XING YAHAO](mailto:48758247+xyyolab@users.noreply.github.com) | http_load:add page (#3914) | 2020-04-04T12:28:51 | [f68c94e85c91](https://github.com/tldr-pages/tldr/commit/f68c94e85c91fb415b6e28f92b83e2525ae731e5)

