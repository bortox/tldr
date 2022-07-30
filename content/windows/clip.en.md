---
author: ['Owen Voke', 'bl-ue', 'Lucas Gabriel Schneider', 'NNRepos']
date: 1621541621
title: "clip"
description: "clip, Copy input content to the Windows clipboard."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/clip>.

- Pipe command-line output to the Windows clipboard:

```bash
dir | clip
```

- Copy the contents of a file to the Windows clipboard:

```bash
clip < path/to/file.ext
```

- Copy text with a trailing newline to the Windows clipboard:

```bash
echo some text | clip
```

- Copy text without a trailing newline to the Windows clipboard:

```bash
echo | set /p="some text" | clip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[NNRepos](mailto:45516943+NNRepos@users.noreply.github.com) | clip: add examples, fix typos (#3503) | 2019-10-31T18:36:53 | [254cf9f450ac](https://github.com/tldr-pages/tldr/commit/254cf9f450acdcf32dcd8d69775ae65c34431205)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | clip: add page (#2397) | 2018-10-09T00:07:11 | [47ff6a5631a2](https://github.com/tldr-pages/tldr/commit/47ff6a5631a2fade56d1860c9aa3223dfd3b554d)

