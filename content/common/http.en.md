---
author: ['Waldir Pimenta', 'Schneider', 'Agniva De Sarker', 'pxgamer', 'Eric Nielsen', 'Igor Shubovych', 'Jakub Roztocil', 'Jakub Roztočil', 'Nicolas Kosinski', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629050349
title: "http, TLDR Pages"
description: "http, HTTPie: HTTP client, aims to be easier to use than cURL."
categories: "common"
---
> More information: <https://httpie.org>.

- Download a URL to a file:

```bash
http --download example.org
```

- Send form-encoded data:

```bash
http --form example.org name='bob' profile_picture@'bob.png'
```

- Send JSON object:

```bash
http example.org name='bob'
```

- Specify an HTTP method:

```bash
http HEAD example.org
```

- Include an extra header:

```bash
http example.org X-MyHeader:123
```

- Pass a username and password for server authentication:

```bash
http --auth username:password example.org
```

- Specify raw request body via stdin:

```bash
cat data.txt | http PUT example.org
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | http: use long arguments (#5878) | 2021-05-04T09:25:21 | [a312432c3696](https://github.com/tldr-pages/tldr/commit/a312432c36964fc1d70858b0c8fdec252fe13475)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Schneider](mailto:lucas.schneider@sap.com) | http: remove adjectives | 2020-02-20T18:00:28 | [0c6d326d843d](https://github.com/tldr-pages/tldr/commit/0c6d326d843d2634e0bcd2571020db16bd2717a9)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | http: add link to homepage | 2019-06-07T23:58:59 | [f2621576fc7f](https://github.com/tldr-pages/tldr/commit/f2621576fc7f9f6c4cc6477139b68b995458303d)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | http: Variable supplied parameters between {{}} (#1125) Missing in the last example. | 2016-10-21T17:56:02 | [2f5af7f829b6](https://github.com/tldr-pages/tldr/commit/2f5af7f829b6e1024352cd8f475feffc5a163c25)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | http: add the missing example to HTTPie (see discussion in #808) | 2016-02-29T10:47:42 | [30433c622bf5](https://github.com/tldr-pages/tldr/commit/30433c622bf590c14e138e752e5712227700cc82)
[Jakub Roztočil](mailto:jakub@roztocil.co) | Commands-- | 2016-02-29T07:26:07 | [9179bb7131d6](https://github.com/tldr-pages/tldr/commit/9179bb7131d6f4723ecb050d4821d138e7ef6df2)
[Jakub Roztočil](mailto:jakub@roztocil.co) | Reduced the number of examples | 2016-02-28T18:22:04 | [927e44ca261e](https://github.com/tldr-pages/tldr/commit/927e44ca261eb542f400cfc478d5b60020296809)
[Jakub Roztocil](mailto:jakub@roztocil.co) | http: add | 2016-02-28T11:17:45 | [1d062a94f057](https://github.com/tldr-pages/tldr/commit/1d062a94f05793e921deb603ed44208dc5841765)

