---
author: ['Srinivasan R', 'Emily Grace Seville', 'Ruben Vereecken', 'Chriztian Steinmeier', 'Quang Tran']
date: 1644837703
title: "xsltproc, TLDR Pages"
description: "xsltproc, Transform XML with XSLT to produce output (usually HTML or XML)."
categories: "osx"
---
> More information: <http://www.xmlsoft.org/xslt/xsltproc.html>.

- Transform an XML file with a specific XSLT stylesheet:

```bash
xsltproc --output output.html stylesheet.xslt xmlfile.xml
```

- Pass a value to a parameter in the stylesheet:

```bash
xsltproc --output output.html --stringparam "name" "value" stylesheet.xslt xmlfile.xml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Quang Tran](mailto:quangtran@mailbox.org) | xsltproc: add missing documentation link (#7267) | 2021-10-28T01:52:22 | [771978fa47c6](https://github.com/tldr-pages/tldr/commit/771978fa47c668aba3bdea6b330fe749ade8eeaa)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[Chriztian Steinmeier](mailto:chriztian@steinmeier.dk) | Correct tokens | 2014-03-04T21:10:51 | [0a67ee4d957f](https://github.com/tldr-pages/tldr/commit/0a67ee4d957f912a486a9935702eb143728f0212)
[Chriztian Steinmeier](mailto:chriztian@steinmeier.dk) | Add page for `xsltproc` | 2014-03-04T21:08:56 | [5a2980ea7722](https://github.com/tldr-pages/tldr/commit/5a2980ea7722e8033d6787fc98ddde8ab09eef7f)

