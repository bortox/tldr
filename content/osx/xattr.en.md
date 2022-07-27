---
author: ['Charles Merriam', 'meowmeowcat', 'Waldir Pimenta', 'Vlad']
date: 1635858124
title: "xattr, TLDR Pages"
description: "xattr, Utility to work with extended filesystem attributes."
categories: "osx"
---
> More information: <https://ss64.com/osx/xattr.html>.

- List key:value extended attributes for a given file:

```bash
xattr -l file
```

- Write an attribute for a given file:

```bash
xattr -w attribute_key attribute_value file
```

- Delete an attribute from a given file:

```bash
xattr -d com.apple.quarantine file
```

- Delete all extended attributes from a given file:

```bash
xattr -c file
```

- Recursively delete an attribute in a given directory:

```bash
xattr -rd attribute_key directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osascript, xattr, pmset, say, screencapture: add link (#7368) | 2021-11-02T14:02:04 | [b85bc433fb19](https://github.com/tldr-pages/tldr/commit/b85bc433fb1916e6fd9b053f9db24284d11fc4e6)
[Charles Merriam](mailto:charles.merriam@gmail.com) | xattr: Add removing quarantine; the by far most common use of this command (#1668) | 2017-12-13T04:53:53 | [f38e8f463f7c](https://github.com/tldr-pages/tldr/commit/f38e8f463f7c827867e53289b13ed3f57b350a55)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | xattr: slightly clearer description | 2016-06-21T00:50:33 | [c46d662c947e](https://github.com/tldr-pages/tldr/commit/c46d662c947e61bf3fb304577c43ddcce265c78b)
[Vlad](mailto:vpoltava@gmail.com) | xattr: add page (#895) | 2016-06-21T00:47:41 | [da1ac91081fa](https://github.com/tldr-pages/tldr/commit/da1ac91081fac0efa3ae440c329ce19586b01a3e)

