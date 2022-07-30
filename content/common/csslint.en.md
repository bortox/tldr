---
author: ['Andrew Dassonville', 'pxgamer', 'Seth Falco']
date: 1629050349
title: "csslint"
description: "csslint, A linter for CSS code."
categories: "common"
---
> More information: <https://github.com/CSSLint/csslint/wiki/Command-line-interface>.

- Lint a single CSS file:

```bash
csslint file.css
```

- Lint multiple CSS files:

```bash
csslint file1.css file2.css file3.css
```

- List all possible style rules:

```bash
csslint --list-rules
```

- Specify certain rules as errors (which result in a non-zero exit code):

```bash
csslint --errors=errors,universal-selector,imports file.css
```

- Specify certain rules as warnings:

```bash
csslint --warnings=box-sizing,selector-max,floats file.css
```

- Specify certain rules to ignore:

```bash
csslint --ignore=ids,rules-count,shorthand file.css
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | csslint: add link to homepage | 2019-06-09T18:53:49 | [9e515f9607aa](https://github.com/tldr-pages/tldr/commit/9e515f9607aaea21962d1b4e4f4cf458dffe06e7)
[Andrew Dassonville](mailto:dassonville.andrew@gmail.com) | csslint: add page (#1723) | 2017-12-01T07:25:48 | [c24e05789e26](https://github.com/tldr-pages/tldr/commit/c24e05789e26d70f4eb5a22f8a7e57795c190190)

