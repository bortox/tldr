---
author: ['lord63', 'ayakashi', 'Ruben Vereecken', 'Agniva De Sarker', 'pxgamer', 'cattail', 'Romain Prieto', 'rprieto', 'Jaseem Abid', 'Agam Agarwal', 'Balázs Úr', 'Starbeamrainbowlabs']
date: 1609538180
title: "nc, TLDR Pages"
description: "nc, Netcat is a versatile utility for working with TCP or UDP data."
categories: "common"
---
> More information: <https://nmap.org/ncat>.

- Listen on a specified port and print any data received:

```bash
nc -l port
```

- Connect to a certain port:

```bash
nc ip_address port
```

- Set a timeout:

```bash
nc -w timeout_in_seconds ipaddress port
```

- Keep the server up after the client detaches:

```bash
nc -k -l port
```

- Keep the client up even after EOF:

```bash
nc -q timeout ip_address
```

- Scan the open ports of a specified host:

```bash
nc -v -z ip_address port
```

- Act as proxy and forward data from a local TCP port to the given remote host:

```bash
nc -l local_port | nc hostname remote_port
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | nc: remove redundant examples | 2021-01-01T22:56:20 | [06b697b9f7e8](https://github.com/tldr-pages/tldr/commit/06b697b9f7e84cfb93a70f2629a0e3ef97620df8)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | nc: fix grammar | 2021-01-01T22:56:20 | [653dbf065b05](https://github.com/tldr-pages/tldr/commit/653dbf065b05bf51df335e4e5da3623971cf761b)
[pxgamer](mailto:owzie123@gmail.com) | nc: add link to homepage | 2019-06-04T21:29:40 | [75bd2524506d](https://github.com/tldr-pages/tldr/commit/75bd2524506d8707027a2a19785c71889d166c6c)
[Jaseem Abid](mailto:jaseemabid@monzo.com) | nc: Improve title and some examples | 2019-03-04T19:42:45 | [d498c5303162](https://github.com/tldr-pages/tldr/commit/d498c53031626790a1d93c6328f61c4b446f421d)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Agam Agarwal](mailto:agammaster@gmail.com) | Removed useless use of cat | 2016-07-22T07:51:32 | [3250be5beb7e](https://github.com/tldr-pages/tldr/commit/3250be5beb7e28a7c47299587cb09e3bf84f8167)
[ayakashi](mailto:gwanmax@gmail.com) | Update nc.md | 2016-06-13T05:54:36 | [c64932099b02](https://github.com/tldr-pages/tldr/commit/c64932099b02e8603967730aa7930611d1d26dca)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Romain Prieto](mailto:choicesmade@gmail.com) | nc: fix list syntax | 2014-03-08T03:46:34 | [b24b3c0270ee](https://github.com/tldr-pages/tldr/commit/b24b3c0270eec7f02d10945abccb83ef16e903a5)
[cattail](mailto:zhongchiyu@gmail.com) | improve nc.md add server & stay up | 2014-03-08T03:37:44 | [fff41a3604ac](https://github.com/tldr-pages/tldr/commit/fff41a3604ac761b6fe4603f0e866b5f91d8b80f)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

