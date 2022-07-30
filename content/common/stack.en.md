---
author: ['Wisnu Adi Nurcahyo', 'Waldir Pimenta', 'Max Strübing', 'Sibi', 'pxgamer']
date: 1574626115
title: "stack"
description: "stack, Tool for managing Haskell projects."
categories: "common"
---
> More information: <https://github.com/commercialhaskell/stack>.

- Create a new package:

```bash
stack new package_name template_name
```

- Compile a package:

```bash
stack build
```

- Run tests inside a package:

```bash
stack test
```

- Compile a project and re-compile every time a file changes:

```bash
stack build --file-watch
```

- Compile a project and execute a command after compilation:

```bash
stack build --exec "command"
```

- Run a program and pass an argument to it:

```bash
stack exec program_name -- argument
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sibi](mailto:sibi@psibi.in) | Clarify stack command (#3614) | 2019-11-24T21:08:35 | [bf696e0ccd2f](https://github.com/tldr-pages/tldr/commit/bf696e0ccd2fb849d432dee74e5926d4a25c355b)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | stack: add link to homepage | 2019-05-29T14:41:10 | [aafad312349f](https://github.com/tldr-pages/tldr/commit/aafad312349f4dd447f01e7e9074d62aa8ceed50)
[Wisnu Adi Nurcahyo](mailto:nurcahyo@protonmail.com) | stack: add exec command (#1816) | 2017-12-19T13:01:07 | [a4619576259a](https://github.com/tldr-pages/tldr/commit/a4619576259a77d76b97608ede1e70c87a6f5f87)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | stack: fix capitalization of Haskell | 2017-10-01T19:54:34 | [83bae850f4a7](https://github.com/tldr-pages/tldr/commit/83bae850f4a7355ab90236ec2fea86d1a595e5da)
[Max Strübing](mailto:mxstrbng@gmail.com) | stack: add page (#1509) | 2017-10-01T19:53:11 | [48cfe76ee81e](https://github.com/tldr-pages/tldr/commit/48cfe76ee81e4940728e172b57e4514bc03edb0f)

