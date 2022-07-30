---
author: ['Quentin']
date: 1603908366
title: "surfraw"
description: "surfraw, CLI to query a variety of web search engines."
categories: "common"
---
> Consists of a collection of elvi, each of which knows how to search a specific website.

> More information: <http://surfraw.org>.

- Display the list of supported website search scripts (elvi):

```bash
surfraw -elvi
```

- Open the elvi's results page for a specific search in the browser:

```bash
surfraw elvi "search_terms"
```

- Display an elvi description and its specific options:

```bash
surfraw elvi -local-help
```

- Search using an elvi with specific options and open the results page in the browser:

```bash
surfraw elvi elvi_options "search_terms"
```

- Display the URL to the elvi's results page for a specific search:

```bash
surfraw -print elvi "search_terms"
```

- Search using the alias:

```bash
sr elvi "search_terms"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Quentin](mailto:quentin.bettoum@mailo.com) | surfraw: add page (#4771) | 2020-10-28T19:06:06 | [e2f4310506ee](https://github.com/tldr-pages/tldr/commit/e2f4310506ee1143b9b4e409e7528481d3ce8837)

