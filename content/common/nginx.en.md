---
author: ['Ben Ripkens', 'Igor Shubovych', 'zzgigi2005@163.com', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Joe Archer', 'Leandro Ostera', 'Ruben Vereecken']
date: 1559564381
title: "nginx"
description: "nginx, Nginx web server."
categories: "common"
---
> More information: <https://nginx.org/en/>.

- Start server with the default config file:

```bash
nginx
```

- Start server with a custom config file:

```bash
nginx -c config_file
```

- Start server with a prefix for all relative paths in the config file:

```bash
nginx -c config_file -p prefix/for/relative/paths
```

- Test the configuration without affecting the running server:

```bash
nginx -t
```

- Reload the configuration by sending a signal with no downtime:

```bash
nginx -s reload
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | nginx: small grammar fixes (#1537) | 2017-10-11T18:11:20 | [a6a29fcf09fd](https://github.com/tldr-pages/tldr/commit/a6a29fcf09fd0799e76ad132c6ae9be5ac441115)
[Leandro Ostera](mailto:leandro@ostera.io) | Left most common sample only | 2016-02-13T00:31:33 | [b7bca90124e8](https://github.com/tldr-pages/tldr/commit/b7bca90124e8a3938452659fffa8c75fbe7b38b7)
[zzgigi2005@163.com](mailto:zzgigi2005@163.com) | nginx:add stop,quit,reopen,reload | 2016-01-10T12:22:06 | [5283e9111396](https://github.com/tldr-pages/tldr/commit/5283e9111396f356737460d356716a7010f73310)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Joe Archer](mailto:joe@laserred.co) | nginx: add -t example | 2016-01-04T11:34:40 | [31234c9e4bc2](https://github.com/tldr-pages/tldr/commit/31234c9e4bc28c0c9f64013c016c9a4025f52805)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | nginx: fix tokens | 2015-12-21T15:42:10 | [2c8a7941bc0f](https://github.com/tldr-pages/tldr/commit/2c8a7941bc0f497df09f988eb66ea2031ca4a4e9)
[Ben Ripkens](mailto:bripkens.dev@gmail.com) | Do not put marketing lingo into nginx page | 2015-12-20T09:35:38 | [2ff7b8de0abb](https://github.com/tldr-pages/tldr/commit/2ff7b8de0abbef9e0e2cb5aa240e5bd2ac70880c)
[Ben Ripkens](mailto:bripkens.dev@gmail.com) | Explain basic nginx commands | 2015-12-20T09:23:33 | [f7e917903ee6](https://github.com/tldr-pages/tldr/commit/f7e917903ee69ee1aad31254006d3f307b1f5b36)

