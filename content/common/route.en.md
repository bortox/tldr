---
author: ['nelsonchung', 'Balázs Úr', 'pxgamer', 'Sadeed', 'Leandro Ostera']
date: 1634106170
title: "route"
description: "route, Use route cmd to set the route table."
categories: "common"
---
> More information: <https://manned.org/route>.

- Display the information of route table:

```bash
route -n
```

- Add route rule:

```bash
sudo route add -net ip_address netmask netmask_address gw gw_address
```

- Delete route rule:

```bash
sudo route del -net ip_address netmask netmask_address dev gw_address
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | rar, read, renice, rev, roll, route, rsync: add link (#6929) | 2021-10-13T08:22:50 | [6583ef2421da](https://github.com/tldr-pages/tldr/commit/6583ef2421da704fdb94b1acb67c70936ccb5ddf)
[pxgamer](mailto:owzie123@gmail.com) | route: fix minor typo | 2019-05-29T14:41:10 | [5c124c4b0f2d](https://github.com/tldr-pages/tldr/commit/5c124c4b0f2dc91b42fc4f0e0ceeb2264bb2d109)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[Leandro Ostera](mailto:leandro@ostera.io) | Fixes trailing whitespace | 2016-02-06T12:09:16 | [4f8751d7ada6](https://github.com/tldr-pages/tldr/commit/4f8751d7ada6e3d0f021bb0886540d4d16641dc8)
[nelsonchung](mailto:chihchun.chung@gmail.com) | Add route.md | 2016-02-03T04:31:55 | [525df4d8c59c](https://github.com/tldr-pages/tldr/commit/525df4d8c59c09e5c370cfa8a5b0ad40c0cdca03)

