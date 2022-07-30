---
author: ['thiswind', 'bl-ue', 'pxgamer', 'marchersimon']
date: 1625253777
title: "httping"
description: "httping, Measure the latency and throughput of a web server."
categories: "common"
---
> More information: <https://manned.org/httping>.

- Ping the specified URL:

```bash
httping -g url
```

- Ping the web server on `host` and `port`:

```bash
httping -h host -p port
```

- Ping the web server on `host` using a TLS connection:

```bash
httping -l -g https://host
```

- Ping the web server on `host` using HTTP basic authentication:

```bash
httping -g http://host -U username -P password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | httping: add link to homepage | 2019-06-07T23:58:59 | [d2fbdb455a08](https://github.com/tldr-pages/tldr/commit/d2fbdb455a082d6774006b00589fe7795b6ed0a0)
[thiswind](mailto:thiswind@gmail.com) | httping: change param of option -g from {{host}} to {{url}} | 2019-02-11T18:11:44 | [6c0eb4249631](https://github.com/tldr-pages/tldr/commit/6c0eb424963181e6ec027526802aa4d7f2dc9b89)
[thiswind](mailto:23764+thiswind@users.noreply.github.com) | httping: add page (#2768) | 2019-02-10T21:06:43 | [6b18a163214a](https://github.com/tldr-pages/tldr/commit/6b18a163214a8dd47736e7027cb10e03e3b32e51)

