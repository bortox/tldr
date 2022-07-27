---
author: ['bl-ue', 'Max Xu', 'Agniva De Sarker', 'Lars Decker', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1645094767
title: "httpie, TLDR Pages"
description: "httpie, A user friendly command-line HTTP tool."
categories: "linux"
---
> More information: <https://github.com/httpie/httpie>.

- Send a GET request (default method with no request data):

```bash
http https://example.com
```

- Send a POST request (default method with request data):

```bash
http https://example.com hello=World
```

- Send a POST request with redirected input:

```bash
http https://example.com < file.json
```

- Send a PUT request with a given JSON body:

```bash
http PUT https://example.com/todos/7 hello=world
```

- Send a DELETE request with a given request header:

```bash
http DELETE https://example.com/todos/7 API-Key:foo
```

- Show the whole HTTP exchange (both request and response):

```bash
http -v https://example.com
```

- Download a file:

```bash
http --download https://example.com
```

- Follow redirects and show intermediary requests and responses:

```bash
http --follow --all https://example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lars Decker](mailto:lars.decker@gmail.com) | http: add --follow example (#7737) | 2022-02-17T11:46:07 | [b02d5dc9f1f4](https://github.com/tldr-pages/tldr/commit/b02d5dc9f1f4eb7e1016b2b08e4deaa0b4ed27d1)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | http: update to example.com And also fix a minor typo | 2017-12-22T04:57:22 | [b60842e5a999](https://github.com/tldr-pages/tldr/commit/b60842e5a999622e3c28b741ec766e6cb6cedd1b)
[Max Xu](mailto:xuhuan@live.cn) | Update httpie.md | 2017-12-22T04:00:30 | [5a6a7135141f](https://github.com/tldr-pages/tldr/commit/5a6a7135141f67700bed141cfcb1e2e47afc67fc)
[Max Xu](mailto:xuhuan@live.cn) | Update httpie.md | 2017-12-20T13:27:08 | [9c2826882981](https://github.com/tldr-pages/tldr/commit/9c2826882981b6c5a0970d135c44866c5a1533c6)
[Max Xu](mailto:xuhuan@live.cn) | httpie.md: add page | 2017-12-20T04:51:32 | [b62473aa25c3](https://github.com/tldr-pages/tldr/commit/b62473aa25c3e56d90722556aa2787fae72eec73)

