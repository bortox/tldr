---
author: ['lord63', 'Peter Tripp', 'pxgamer', 'Ruben Vereecken']
date: 1559133670
title: "salt-call"
description: "salt-call, Invoke salt locally on a salt minion."
categories: "common"
---
> More information: <https://docs.saltstack.com/ref/cli/salt-call.html>.

- Perform a highstate on this minion:

```bash
salt-call state.highstate
```

- Perform a highstate dry-run, compute all changes but don't actually perform them:

```bash
salt-call state.highstate test=true
```

- Perform a highstate with verbose debugging output:

```bash
salt-call -l debug state.highstate
```

- List this minion's grains:

```bash
salt-call grains.items
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | salt-call: update link to homepage | 2019-05-29T14:41:10 | [01968311af9f](https://github.com/tldr-pages/tldr/commit/01968311af9fb038cf77f4cdcdb52027a37cc839)
[pxgamer](mailto:owzie123@gmail.com) | salt-call: add link to homepage | 2019-05-29T14:41:10 | [5cd4392a97c1](https://github.com/tldr-pages/tldr/commit/5cd4392a97c1d8aa3b83a16bb5f0cfb994da6dfc)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Peter Tripp](mailto:petertripp@gmail.com) | Added saltstack. | 2014-07-27T21:36:19 | [8610d9ce19b0](https://github.com/tldr-pages/tldr/commit/8610d9ce19b0e55d0263f38be04faec5549cc1c0)

