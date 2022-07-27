---
author: ['pxgamer', 'David Haynes', 'Lucas Gabriel Schneider', 'Schneider']
date: 1570937284
title: "hugo, TLDR Pages"
description: "hugo, Template-based static site generator. Uses modules, components, and themes."
categories: "common"
---
> More information: <https://gohugo.io>.

- Create a new Hugo site:

```bash
hugo new site path/to/site
```

- Create a new Hugo theme (themes may also be downloaded from https://themes.gohugo.io/):

```bash
hugo new theme theme_name
```

- Create a new page:

```bash
hugo new section_name/filename
```

- Build a site to the `./public/` directory:

```bash
hugo
```

- Build a site including pages that are marked as a "draft":

```bash
hugo --buildDrafts
```

- Build a site to a given directory:

```bash
hugo --destination path/to/destination
```

- Build a site, start up a webserver to serve it, and automatically reload when pages are edited:

```bash
hugo server
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | Update pages/common/hugo.md Co-Authored-By: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2019-10-13T05:28:04 | [3dc031f91462](https://github.com/tldr-pages/tldr/commit/3dc031f9146240f1ac7203c209c3aa354c335a64)
[Schneider](mailto:lucas.schneider@sap.com) | multiple pages: rephrase without adjectives | 2019-10-13T05:28:04 | [42152ed45923](https://github.com/tldr-pages/tldr/commit/42152ed459230c2b244529f0c5990335e0057c6c)
[pxgamer](mailto:owzie123@gmail.com) | hugo: add link to homepage | 2019-06-07T23:58:59 | [e0ca1aec162d](https://github.com/tldr-pages/tldr/commit/e0ca1aec162d922916d80b251940085999505df9)
[David Haynes](mailto:dhaynes3@gmu.edu) | hugo: omit subject - Remove uses of "your" and "you" | 2017-05-26T16:32:52 | [5ea8b54d903b](https://github.com/tldr-pages/tldr/commit/5ea8b54d903b2ea21020db51ec06c150f95fabfc)
[David Haynes](mailto:dhaynes3@gmu.edu) | hugo: modify language - hugo -> Hugo - lowercase the description - plain URL - remove the extension token - do not use relative [...] | 2017-05-26T16:32:52 | [474f188b8831](https://github.com/tldr-pages/tldr/commit/474f188b8831cb7d156366f0538d93bca0b6adf9)
[David Haynes](mailto:dhaynes3@gmu.edu) | hugo: add page - Add in `hugo` commands essential to getting a site up and running. - This is defined as: - A site existing - A theme [...] | 2017-05-26T16:32:52 | [0dea4539f3e9](https://github.com/tldr-pages/tldr/commit/0dea4539f3e9f3ed234ae4878150534a1638bc2b)

