---
author: ['Raffaele Mignone']
date: 1570030508
title: "shiori"
description: "shiori, Simple bookmark manager built with Go."
categories: "common"
---
> More information: <https://github.com/go-shiori/shiori>.

- Import bookmarks from HTML Netscape bookmark format file:

```bash
shiori import path/to/bookmarks.html
```

- Save the specified URL as bookmark:

```bash
shiori add url
```

- List the saved bookmarks:

```bash
shiori print
```

- Open the saved bookmark in a browser:

```bash
shiori open bookmark_id
```

- Start the web interface for managing bookmarks at port 8181:

```bash
shiori serve --port 8181
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Raffaele Mignone](mailto:git@norangeb.it) | shiori: add page (#3289) | 2019-10-02T17:35:08 | [4254f54ad41e](https://github.com/tldr-pages/tldr/commit/4254f54ad41ef9101c03ee1f3726b96b76edcfba)

