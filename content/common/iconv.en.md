---
author: ['Waldir Pimenta', 'Kyle', 'Ruben Vereecken', 'Erik Vesteraas', 'Lucas Gabriel Schneider']
date: 1629747204
title: "iconv, TLDR Pages"
description: "iconv, Converts text from one encoding to another."
categories: "common"
---
> More information: <https://manned.org/iconv>.

- Convert file to a specific encoding, and print to stdout:

```bash
iconv -f from_encoding -t to_encoding input_file
```

- Convert file to the current locale's encoding, and output to a file:

```bash
iconv -f from_encoding input_file > output_file
```

- List supported encodings:

```bash
iconv -l
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | iconv: more explicit example descriptions (#863) | 2016-05-03T09:27:32 | [ebeed606d96a](https://github.com/tldr-pages/tldr/commit/ebeed606d96acd30b68d6a2cd872d1d569044cd8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Erik Vesteraas](mailto:erik@vestera.as) | Added docs for iconv | 2014-09-03T22:21:30 | [129f3cdc3a66](https://github.com/tldr-pages/tldr/commit/129f3cdc3a66cbb0712baf9f640666d9e2403f6a)

