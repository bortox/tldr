---
author: ['Igor Shubovych', 'Schneider', 'Srinivasan R', 'Miguel Mendes', 'Marco Bonelli', 'Nir Elbaz', 'bl-ue', 'Ruben Vereecken']
date: 1615671899
title: "ab"
description: "ab, Apache HTTP server benchmarking tool."
categories: "common"
---
> More information: <https://httpd.apache.org/docs/current/programs/ab.html>.

- Execute 100 HTTP GET requests to a given URL:

```bash
ab -n 100 url
```

- Execute 100 HTTP GET requests, in concurrent batches of 10, to a URL:

```bash
ab -n 100 -c 10 url
```

- Execute 100 HTTP POST requests to a URL, using a JSON payload from a file:

```bash
ab -n 100 -T application/json -p path/to/file.json url
```

- Use HTTP [K]eep Alive, i.e. perform multiple requests within one HTTP session:

```bash
ab -k url
```

- Set the maximum number of seconds to spend for benchmarking:

```bash
ab -t 60 url
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | ab: update grammar; update link (#5433) | 2021-03-13T22:44:59 | [8f2ed246f761](https://github.com/tldr-pages/tldr/commit/8f2ed246f7614df6e815b9eefae053a0f64df920)
[Nir Elbaz](mailto:nire0510@gmail.com) | ab: add POST request example (#3805) * Update ab.md Sending POST requests * Update pages/common/ab.md Co-Authored-By: Marco Bonelli [...] | 2020-01-29T12:53:07 | [8d70685f0ba7](https://github.com/tldr-pages/tldr/commit/8d70685f0ba73aece077a2b4cf0e59a04a37d8e7)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | ab.md added homepage | 2019-04-11T09:49:15 | [777d1256c630](https://github.com/tldr-pages/tldr/commit/777d1256c630c2563ec50c6d624372682be5fbfa)
[Miguel Mendes](mailto:mendesmiguel@users.noreply.github.com) | ab: add new examples (#2514) | 2018-11-03T11:30:41 | [8aea0e5773a2](https://github.com/tldr-pages/tldr/commit/8aea0e5773a23d4d58f8b588c822af7dd861ab95)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Fix ab page to conform common standards | 2014-05-07T16:34:50 | [f063d3b670c6](https://github.com/tldr-pages/tldr/commit/f063d3b670c65fa6c13664927fb2d6d3debf5080)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Pages: ab | 2014-05-07T15:03:43 | [adafccee36b6](https://github.com/tldr-pages/tldr/commit/adafccee36b693619f117da9777b905a84a017dd)

