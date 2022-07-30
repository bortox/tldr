---
author: ['Agniva De Sarker', 'Jonas Brusman', 'Peter Tripp', 'rprieto', 'Srinivasan R', 'pxgamer', 'klew', 'Seth Falco', 'Ruben Vereecken']
date: 1629050349
title: "redis-cli"
description: "redis-cli, Opens a connection to a Redis server."
categories: "common"
---
> More information: <https://redis.io/topics/rediscli>.

- Connect to the local server:

```bash
redis-cli
```

- Connect to a remote server on the default port (6379):

```bash
redis-cli -h host
```

- Connect to a remote server specifying a port number:

```bash
redis-cli -h host -p port
```

- Connect to a remote server specifying a URI:

```bash
redis-cli -u uri
```

- Specify a password:

```bash
redis-cli -a password
```

- Execute Redis command:

```bash
redis-cli redis_command
```

- Connect to the local cluster:

```bash
redis-cli -c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[klew](mailto:417879751@qq.com) | redis-cli: add new argument -c (#5022) | 2020-12-12T04:13:57 | [5ccf69e1c38d](https://github.com/tldr-pages/tldr/commit/5ccf69e1c38d49a3f459e4e8e5c8e51e35a8cebb)
[Jonas Brusman](mailto:jonas@brusman.se) | redis-cli: add URI connection example (#4930) | 2020-11-04T15:39:54 | [c316c2627dd7](https://github.com/tldr-pages/tldr/commit/c316c2627dd7a8cc318c90340063557500f8478a)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | redis-cli: add link to homepage | 2019-05-29T14:41:10 | [d94719bd9dbc](https://github.com/tldr-pages/tldr/commit/d94719bd9dbc3cf5937c02104e947a445a03e2ef)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Peter Tripp](mailto:petertripp@gmail.com) | Redis-cli: Condense, add note about default port. | 2016-01-20T12:39:49 | [52560585f970](https://github.com/tldr-pages/tldr/commit/52560585f970fe733ee0604b6292a39ebefceda0)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

