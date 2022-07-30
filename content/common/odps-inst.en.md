---
author: ['程亦超(何兮)', 'marchersimon']
date: 1623219131
title: "odps inst"
description: "odps inst, Manage instances in ODPS (Open Data Processing Service)."
categories: "common"
---
> See also `odps`.

> More information: <https://www.alibabacloud.com/help/doc-detail/27971.htm>.

- Show instances created by current user:

```bash
show instances;
```

- Describe the details of an instance:

```bash
desc instance instance_id;
```

- Check the status of an instance:

```bash
status instance_id;
```

- Wait on the termination of an instance, printing log and progress information until then:

```bash
wait instance_id;
```

- Kill an instance:

```bash
kill instance_id;
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | opds*: add link and see also note (#6074) | 2021-06-09T08:12:11 | [b139da2bb6f8](https://github.com/tldr-pages/tldr/commit/b139da2bb6f8c8cb24c1948278fdd6247ec7ffd3)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-inst: update Change-Id: I854a7c53372731e048e119aef0466638ec2cf9d9 | 2016-05-15T10:53:16 | [ef5ad25e56f9](https://github.com/tldr-pages/tldr/commit/ef5ad25e56f95831f7dd462655114a9a25ec5595)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-inst: update Change-Id: Id1b21ce652ed7410878e570ba51a9c9ec0607848 | 2016-05-14T05:11:18 | [cc90103f8d27](https://github.com/tldr-pages/tldr/commit/cc90103f8d2797df8bb0c8ce6c8717738e3b6817)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-inst: add page Change-Id: I477c1dabde9a2e517632b38de2e5e878a6fd835d | 2016-05-12T16:10:00 | [ce67b801ebd9](https://github.com/tldr-pages/tldr/commit/ce67b801ebd90e1a65650e9a7f6bb409c996cf61)

