---
author: ['Ruben Vereecken', 'lord63', 'pxgamer', 'Peter Tripp']
date: 1559133670
title: "salt-key, TLDR Pages"
description: "salt-key, Manages salt minion keys on the salt master."
categories: "common"
---
> Needs to be run on the salt master, likely as root or with sudo.

> More information: <https://docs.saltstack.com/ref/cli/salt-key.html>.

- List all accepted, unaccepted and rejected minion keys:

```bash
salt-key -L
```

- Accept a minion key by name:

```bash
salt-key -a MINION_ID
```

- Reject a minion key by name:

```bash
salt-key -r MINION_ID
```

- Print fingerprints of all public keys:

```bash
salt-key -F
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | salt-key: update link to homepage | 2019-05-29T14:41:10 | [7026ba70e4c2](https://github.com/tldr-pages/tldr/commit/7026ba70e4c22fc3efcedb62ed89a5ca60aa1492)
[pxgamer](mailto:owzie123@gmail.com) | salt-key: add link to homepage | 2019-05-29T14:41:10 | [5f004ed32505](https://github.com/tldr-pages/tldr/commit/5f004ed32505450ad19af2eb86d374e7879880cb)
[Peter Tripp](mailto:petertripp@gmail.com) | salt-key: split combined examples. | 2016-01-20T12:41:38 | [16549758f1e0](https://github.com/tldr-pages/tldr/commit/16549758f1e06583a97dd362e0d38996e3653104)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Peter Tripp](mailto:petertripp@gmail.com) | Added saltstack. | 2014-07-27T21:36:19 | [8610d9ce19b0](https://github.com/tldr-pages/tldr/commit/8610d9ce19b0e55d0263f38be04faec5549cc1c0)

