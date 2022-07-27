---
author: ['Juri', 'pxgamer', 'Hayden Schiff', 'sebastientinel']
date: 1606737972
title: "lwp-request, TLDR Pages"
description: "lwp-request, Simple command-line HTTP client."
categories: "common"
---
> Built with libwww-perl.

> More information: <https://metacpan.org/pod/lwp-request>.

- Make a simple GET request:

```bash
lwp-request -m GET http://example.com/some/path
```

- Upload a file with a POST request:

```bash
lwp-request -m POST http://example.com/some/path < path/to/file
```

- Make a request with a custom user agent:

```bash
lwp-request -H 'User-Agent: user_agent -m METHOD http://example.com/some/path
```

- Make a request with HTTP authentication:

```bash
lwp-request -C username:password -m METHOD http://example.com/some/path
```

- Make a request and print request headers:

```bash
lwp-request -U -m METHOD http://example.com/some/path
```

- Make a request and print response headers and status chain:

```bash
lwp-request -E -m METHOD http://example.com/some/path
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | lwp-request: removed unnecessary usage of cat (#4989) | 2020-11-30T13:06:12 | [b20e80a60f03](https://github.com/tldr-pages/tldr/commit/b20e80a60f0317e73c0a402429a008340f4526a6)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[pxgamer](mailto:owzie123@gmail.com) | lwp-request: add link to homepage | 2019-06-06T04:42:48 | [9969170694dc](https://github.com/tldr-pages/tldr/commit/9969170694dc047bfed40b0ee19b37895ce34086)
[Hayden Schiff](mailto:oxguy3@gmail.com) | lwp-request: reference to libwww-perl | 2016-01-24T08:05:29 | [7e582eebf030](https://github.com/tldr-pages/tldr/commit/7e582eebf030655a49d5d9749c404c5d081957f7)
[Hayden Schiff](mailto:oxguy3@gmail.com) | added lwp-request | 2016-01-22T00:10:23 | [fdaf29d920d6](https://github.com/tldr-pages/tldr/commit/fdaf29d920d68925e96780c2af0ada32493c9ff6)

