---
author: ['Pierre Rudloff']
date: 1658181080
title: "varnishlog, TLDR Pages"
description: "varnishlog, Display Varnish logs."
categories: "common"
---
> More information: <https://varnish-cache.org/docs/trunk/reference/varnishlog.html>.

- Display logs in real time:

```bash
varnishlog
```

- Only display requests to a specific domain:

```bash
varnishlog -q 'ReqHeader eq "Host: example.com"'
```

- Only display POST requests:

```bash
varnishlog -q 'ReqMethod eq "POST"'
```

- Only display requests to a specific path:

```bash
varnishlog -q 'ReqURL eq "/path"'
```

- Only display requests to paths matching a regular expression:

```bash
varnishlog -q 'ReqURL ~ "regex"'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | varnishlog: add page (#8169) | 2022-07-18T23:51:20 | [7d6bd2e6cce7](https://github.com/tldr-pages/tldr/commit/7d6bd2e6cce754923ca1f8aab125af482e17be6b)

