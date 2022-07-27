---
author: ['Waldir Pimenta', 'haydenbetts', 'Seth Falco', 'syleung']
date: 1633350747
title: "xmllint, TLDR Pages"
description: "xmllint, XML parser and linter that supports XPath, a syntax for navigating XML trees."
categories: "common"
---
> More information: <https://manned.org/xmllint>.

- Return all nodes (tags) named "foo":

```bash
xmllint --xpath "//foo" source_file.xml
```

- Return the contents of the first node named "foo" as a string:

```bash
xmllint --xpath "string(//foo)" source_file.xml
```

- Return the href attribute of the second anchor element in an HTML file:

```bash
xmllint --html --xpath "string(//a[2]/@href)" webpage.xhtml
```

- Return human-readable (indented) XML from file:

```bash
xmllint --format source_file.xml
```

- Check that an XML file meets the requirements of its DOCTYPE declaration:

```bash
xmllint --valid source_file.xml
```

- Validate XML against DTD schema hosted online:

```bash
xmllint --dtdvalid URL source_file.xml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/x*: add more information link (#6664) | 2021-10-04T14:32:27 | [99a72c556f56](https://github.com/tldr-pages/tldr/commit/99a72c556f563a928a10ff2c2146ad42d9af2990)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | xmllint: various fixes (#1450) - fix string example, and improve its description - move xpath information to the main description - [...] | 2017-08-25T11:09:36 | [bad0110e8aa2](https://github.com/tldr-pages/tldr/commit/bad0110e8aa2690a04bea087e9253c4a625a21ed)
[haydenbetts](mailto:haydenbetts@gmail.com) | xmllint: add page (#1425) | 2017-07-14T10:36:12 | [0d9a445e2fac](https://github.com/tldr-pages/tldr/commit/0d9a445e2fac4052e3f6da14917731dbfd3d1527)

