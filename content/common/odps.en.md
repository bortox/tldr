---
author: ['程亦超(何兮)', 'bl-ue', 'marchersimon']
date: 1631521281
title: "odps"
description: "odps, Aliyun ODPS (Open Data Processing Service) command-line tool."
categories: "common"
---
> Some subcommands such as `odps inst` have their own usage documentation.

> More information: <https://www.alibabacloud.com/help/doc-detail/27971.htm>.

- Start the command-line with a custom configuration file:

```bash
odpscmd --config=odps_config.ini
```

- Switch current project:

```bash
use project_name;
```

- Show tables in the current project:

```bash
show tables;
```

- Describe a table:

```bash
desc table_name;
```

- Show table partitions:

```bash
show partitions table_name;
```

- Describe a partition:

```bash
desc table_name partition (partition_spec);
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | opds*: add link and see also note (#6074) | 2021-06-09T08:12:11 | [b139da2bb6f8](https://github.com/tldr-pages/tldr/commit/b139da2bb6f8c8cb24c1948278fdd6247ec7ffd3)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps: miss = Change-Id: Ia78ec31af468f233676011f14e684e62c0098dcf | 2016-05-12T16:15:16 | [9ca879d338aa](https://github.com/tldr-pages/tldr/commit/9ca879d338aa1dcae45ab68ad1d0242f29b5d161)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps: delete one case and add one case Change-Id: I3b6fb2d300a2d27e44110566654fed722fb92441 | 2016-05-11T18:17:52 | [3132be399a6b](https://github.com/tldr-pages/tldr/commit/3132be399a6bcaf7010996a0038b1a39bd4b40e8)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps: reduce num of showcases Change-Id: I677a417cf14170ed9f33781d376e004a6c5ca133 | 2016-05-11T18:13:29 | [8cd264e4f240](https://github.com/tldr-pages/tldr/commit/8cd264e4f240e70184ae09ab9fc67ec7b7680c68)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps: add page Change-Id: If1efc9f677f3e480131a293f6c6bb43aaea40a6b | 2016-05-11T14:39:56 | [4c21b73d8176](https://github.com/tldr-pages/tldr/commit/4c21b73d817622b28403bc97ee92883bb2a2fce6)

