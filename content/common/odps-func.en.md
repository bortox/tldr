---
author: ['程亦超(何兮)', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1623219131
title: "odps func"
description: "odps func, Manage functions in ODPS (Open Data Processing Service)."
categories: "common"
---
> See also `odps`.

> More information: <https://www.alibabacloud.com/help/doc-detail/27971.htm>.

- Show functions in the current project:

```bash
list functions;
```

- Create a Java function using a `.jar` resource:

```bash
create function func_name as path.to.package.Func using 'package.jar';
```

- Create a Python function using a `.py` resource:

```bash
create function func_name as script.Func using 'script.py';
```

- Delete a function:

```bash
drop function func_name;
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | opds*: add link and see also note (#6074) | 2021-06-09T08:12:11 | [b139da2bb6f8](https://github.com/tldr-pages/tldr/commit/b139da2bb6f8c8cb24c1948278fdd6247ec7ffd3)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-func: miss {{ }} Change-Id: Ib9aee491350b060262a04c7e7a4ba869442c9bd4 | 2016-05-15T10:50:36 | [0184a14b9925](https://github.com/tldr-pages/tldr/commit/0184a14b9925d2f3177abf88744ee912530bf768)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | Revert "odps-func: simplify" This reverts commit 2cb618cc6fc57687dea5a4dcfd60c12ba018ab74. | 2016-05-14T05:23:06 | [3779e7d200b5](https://github.com/tldr-pages/tldr/commit/3779e7d200b5490a23d1a36c58a57d2d4073a9ca)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-func: simplify Change-Id: If7053144daac40ee8eeb784b699a850cd0e6792d | 2016-05-13T04:13:47 | [2cb618cc6fc5](https://github.com/tldr-pages/tldr/commit/2cb618cc6fc57687dea5a4dcfd60c12ba018ab74)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-func: update Change-Id: I8cdcdea0bff719bfa37b747c5e020c7f20740dd3 | 2016-05-12T15:11:50 | [5b48f3487720](https://github.com/tldr-pages/tldr/commit/5b48f34877200a98343aa65769f2c6433df76922)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-func: add page Change-Id: Iffbbfff1252d40ef3671f9174a09e54fd1fa6de9 | 2016-05-12T14:29:45 | [3d4bea19cea3](https://github.com/tldr-pages/tldr/commit/3d4bea19cea3721185639fa0b3b17e2b325cca46)

