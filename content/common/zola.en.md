---
author: ['Lucas Gabriel Schneider', 'David']
date: 1581443623
title: "zola"
description: "zola, A static site generator in a single binary with everything built-in."
categories: "common"
---
> More information: <https://www.getzola.org/documentation/getting-started/cli-usage/>.

- Create the directory structure used by Zola at the given directory:

```bash
zola init my_site
```

- Build the whole site in the `public` directory after deleting it:

```bash
zola build
```

- Build the whole site into a different directory:

```bash
zola build --output-dir path/to/output_directory/
```

- Build and serve the site using a local server (default is `127.0.0.1:1111`):

```bash
zola serve
```

- Build all pages just like the build command would, but without writing any of the results to disk:

```bash
zola check
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: rephrase without adjectives (#3846) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> Co-authored-by: [...] | 2020-02-11T18:53:43 | [8211b80c1722](https://github.com/tldr-pages/tldr/commit/8211b80c17221eed9f3f8530eafed3cc3fbd03f1)
[David](mailto:animi.vulpis@gmail.com) | zola: add page (#3492) | 2019-10-28T18:36:24 | [9fc91215f47e](https://github.com/tldr-pages/tldr/commit/9fc91215f47e5bed553e5ee3ec116423f65f1131)

