---
author: ['fejx', '程亦超(何兮)', 'marchersimon']
date: 1623219131
title: "odps resource"
description: "odps resource, Manage resources in ODPS (Open Data Processing Service)."
categories: "common"
---
> See also `odps`.

> More information: <https://www.alibabacloud.com/help/doc-detail/27971.htm>.

- Show resources in the current project:

```bash
list resources;
```

- Add file resource:

```bash
add file filename as alias;
```

- Add archive resource:

```bash
add archive archive.tar.gz as alias;
```

- Add .jar resource:

```bash
add jar package.jar;
```

- Add .py resource:

```bash
add py script.py;
```

- Delete resource:

```bash
drop resource resource_name;
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | opds*: add link and see also note (#6074) | 2021-06-09T08:12:11 | [b139da2bb6f8](https://github.com/tldr-pages/tldr/commit/b139da2bb6f8c8cb24c1948278fdd6247ec7ffd3)
[fejx](mailto:florian.jhn@gmail.com) | Change all occurrences of file_name to filename (#4059) | 2020-05-22T14:31:24 | [4e1662b729ba](https://github.com/tldr-pages/tldr/commit/4e1662b729ba2bc23f7c12f606d41a86a613f8ea)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-resource: update Change-Id: I6f5f3b8a8d2689f7f9649ce7fd628b8c861cc5b0 | 2016-05-12T15:14:27 | [604f0eca6545](https://github.com/tldr-pages/tldr/commit/604f0eca65453f34c7219da4dadbccdf30b1f319)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-resource: typo Change-Id: I5d83e4bc32612498188bae2b4504d5925ff0ea63 | 2016-05-12T14:10:28 | [5ee4156fa720](https://github.com/tldr-pages/tldr/commit/5ee4156fa72084c2e592b4dfcf6d2274800d3c8d)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-resource: update Change-Id: I977753abf297066d3f3f5ef6277775c0114d8030 | 2016-05-12T14:05:36 | [4f24a929128f](https://github.com/tldr-pages/tldr/commit/4f24a929128fe85a6018009d56e5b3ab232f9fc1)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-resource: add page Change-Id: I69552328ad7dbfb8117146bd6cb1cff088f1c5a1 | 2016-05-12T08:18:25 | [d85b054fe502](https://github.com/tldr-pages/tldr/commit/d85b054fe50226a44c1e8fc32deeb1087fc82749)

