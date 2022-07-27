---
author: ['程亦超(何兮)', 'marchersimon']
date: 1623219131
title: "odps tunnel, TLDR Pages"
description: "odps tunnel, Data tunnel in ODPS (Open Data Processing Service)."
categories: "common"
---
> See also `odps`.

> More information: <https://www.alibabacloud.com/help/doc-detail/27971.htm>.

- Download table to local file:

```bash
tunnel download table_name file;
```

- Upload local file to a table partition:

```bash
tunnel upload file table_name/partition_spec;
```

- Upload table specifying field and record delimiters:

```bash
tunnel upload file table_name -fd field_delim -rd record_delim;
```

- Upload table using multiple threads:

```bash
tunnel upload file table_name -threads num;
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | opds*: add link and see also note (#6074) | 2021-06-09T08:12:11 | [b139da2bb6f8](https://github.com/tldr-pages/tldr/commit/b139da2bb6f8c8cb24c1948278fdd6247ec7ffd3)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-tunnel: update Change-Id: Id8f584afafc35874f2046f12d1c886bc77f5d105 | 2016-05-14T04:58:43 | [2c86fb2c8ec6](https://github.com/tldr-pages/tldr/commit/2c86fb2c8ec6b9ed157762fa1838682e10135753)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-tunnel: add page Change-Id: Ie91458c5e6302952ef1adc6779ee19a6b4ea3001 | 2016-05-12T15:46:45 | [8bfc4decba1c](https://github.com/tldr-pages/tldr/commit/8bfc4decba1c833a5bc85522be806e2076c11530)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-tunnel: add page Change-Id: Ic97e03bafdc9761eb18f51f912e4e14da1163f9a | 2016-05-12T15:43:06 | [a1198f3713aa](https://github.com/tldr-pages/tldr/commit/a1198f3713aa792a89669198f573232242d5d367)

