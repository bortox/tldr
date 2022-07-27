---
author: ['pxgamer', 'Vidhi Gupta', 'Matthew Peveler', 'Seth Falco']
date: 1629050349
title: "stolonctl, TLDR Pages"
description: "stolonctl, CLI for Stolon, a cloud native PostgreSQL manager for PostgreSQL high availability."
categories: "common"
---
> More information: <https://github.com/sorintlab/stolon>.

- Get cluster status:

```bash
stolonctl --cluster-name cluster_name --store-backend store_backend --store-endpoints store_endpoints status
```

- Get cluster data:

```bash
stolonctl --cluster-name cluster_name --store-backend store_backend --store-endpoints store_endpoints clusterdata
```

- Get cluster specification:

```bash
stolonctl --cluster-name cluster_name --store-backend store_backend --store-endpoints store_endpoints spec
```

- Update cluster specification with a patch in JSON format:

```bash
stolonctl --cluster-name cluster_name --store-backend store_backend --store-endpoints store_endpoints update --patch 'cluster_spec'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Matthew Peveler](mailto:matt.peveler@gmail.com) | stolonctl: change page title to filename (#5089) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-01-04T21:24:59 | [f44e989c65c5](https://github.com/tldr-pages/tldr/commit/f44e989c65c596a8c5d9502ef5550ebd6e15fede)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | stolonctl: add link to homepage | 2019-05-29T14:41:10 | [6bdb71dcc34f](https://github.com/tldr-pages/tldr/commit/6bdb71dcc34f5276e42f6cc13802c4fef6882d02)
[Vidhi Gupta](mailto:vidhigupta0494@gmail.com) | stolonctl: add page (#2505) | 2018-11-01T13:35:04 | [a365369bad17](https://github.com/tldr-pages/tldr/commit/a365369bad17aee0a045debf6a9d2640dace9cfe)

