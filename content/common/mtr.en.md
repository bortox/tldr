---
author: ['Waldir Pimenta', 'Peter Tripp', 'Francesco Yoshi Gobbo', 'Julia Evans', 'lord63', 'pxgamer', 'Ruben Vereecken']
date: 1650076532
title: "mtr"
description: "mtr, Matt's Traceroute: combined traceroute and ping tool."
categories: "common"
---
> More information: <https://bitwizard.nl/mtr>.

- Traceroute to a host and continuously ping all intermediary hops:

```bash
mtr host
```

- Disable IP address and host name mapping:

```bash
mtr -n host
```

- Generate output after pinging each hop 10 times:

```bash
mtr -w host
```

- Force IP IPv4 or IPV6:

```bash
mtr -4 host
```

- Wait for a given time (in seconds) before sending another packet to the same hop:

```bash
mtr -i seconds host
```

- Display the Autonomous System Number (ASN) for each hop:

```bash
mtr --aslookup hostname
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Julia Evans](mailto:julia@jvns.ca) | mtr: add --aslookup example (#8001) | 2022-04-16T04:35:32 | [d6513baeee8c](https://github.com/tldr-pages/tldr/commit/d6513baeee8ca8b7e27be24e9ae6a87db660ffb6)
[pxgamer](mailto:owzie123@gmail.com) | mtr: add link to homepage | 2019-06-04T21:29:40 | [67e133f2839f](https://github.com/tldr-pages/tldr/commit/67e133f2839fabd330498e25f72e285f790e8606)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | mtr: command description correction applying suggestion from agnivade. | 2018-02-06T18:53:49 | [6dd7701cebea](https://github.com/tldr-pages/tldr/commit/6dd7701cebeac4a1e21f383722eb3af44a74befd)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | wait time addition Added a command to define the wait time before sending another probe to the same hop. | 2018-02-06T18:53:49 | [299fda9c14ac](https://github.com/tldr-pages/tldr/commit/299fda9c14ac9350decef6a9d7ca84af5dcc695b)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | mtr: expand title's acronym in the main desc | 2016-09-29T13:30:52 | [c2fa9d260294](https://github.com/tldr-pages/tldr/commit/c2fa9d260294fa3a57f8bfd032c2d0ab0525bdea)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Peter Tripp](mailto:petertripp@gmail.com) | Added ffmpeg, haxelib, Matt's Traceroute and imagemagick convert. | 2014-05-30T20:27:55 | [66b8ce3fc65d](https://github.com/tldr-pages/tldr/commit/66b8ce3fc65d526613a4886e49c607201d92512f)

