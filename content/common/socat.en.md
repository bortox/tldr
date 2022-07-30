---
author: ['pixel', 'Lucas Gabriel Schneider', 'Ye Ding']
date: 1643706393
title: "socat"
description: "socat, Multipurpose relay (SOcket CAT)."
categories: "common"
---
> More information: <http://www.dest-unreach.org/socat/>.

- Listen to a port, wait for an incoming connection and transfer data to STDIO:

```bash
socat - TCP-LISTEN:8080,fork
```

- Create a connection to a host and port, transfer data in STDIO to connected host:

```bash
socat - TCP4:www.example.com:80
```

- Forward incoming data of a local port to another host and port:

```bash
socat TCP-LISTEN:80,fork TCP4:www.example.com:80
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | socat, sn, slimrb, swig: add more information link (#7733) | 2022-02-01T10:06:33 | [2396c6d791e9](https://github.com/tldr-pages/tldr/commit/2396c6d791e95702a3320ea3b13337f4a34998ea)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: standardize domain examples (#3010) This change standardizes URL examples in tldr-pages to use the canonical [...] | 2019-05-13T15:33:05 | [ce642b6c12dd](https://github.com/tldr-pages/tldr/commit/ce642b6c12dd502fbe0360732d637357a1c420bf)
[Ye Ding](mailto:dygvirus@gmail.com) | Fix grammar mistake | 2016-01-20T02:22:04 | [ac5cc41148b6](https://github.com/tldr-pages/tldr/commit/ac5cc41148b6d61743c6859c4f333b2b5f01f140)
[Ye Ding](mailto:dygvirus@gmail.com) | Fix document style | 2016-01-19T11:53:40 | [df151780648d](https://github.com/tldr-pages/tldr/commit/df151780648d57f657cbf407d1e0dc9e1bb0da0c)
[Ye Ding](mailto:dygvirus@gmail.com) | Add socat page | 2016-01-19T10:00:52 | [2a73da4c90bb](https://github.com/tldr-pages/tldr/commit/2a73da4c90bb79917a1a81b462f92c6b4990cf78)

