---
author: ['Starbeamrainbowlabs', 'bl-ue', 'Seth Falco', 'Marco Bonelli']
date: 1629050349
title: "weasyprint"
description: "weasyprint, Render HTML to PDF or PNG."
categories: "common"
---
> More information: <https://weasyprint.org/>.

- Render an HTML file to PDF:

```bash
weasyprint path/to/input.html path/to/output.pdf
```

- Render an HTML file to PNG, including an additional user stylesheet:

```bash
weasyprint path/to/input.html path/to/output.png --stylesheet path/to/stylesheet.css
```

- Output additional debugging information when rendering:

```bash
weasyprint path/to/input.html path/to/output.pdf --verbose
```

- Specify a custom resolution when outputting to PNG:

```bash
weasyprint path/to/input.html path/to/output.png --resolution 300
```

- Specify a base URL for relative URLs in the input HTML file:

```bash
weasyprint path/to/input.html path/to/output.png --base-url url_or_filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | weasyprint: add page (#2367) | 2018-10-02T12:12:47 | [7b6f488770a8](https://github.com/tldr-pages/tldr/commit/7b6f488770a84a7f0928fa7cb77a320c2da1b3b5)

