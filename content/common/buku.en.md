---
author: ['Noemi', 'Raffaele Mignone']
date: 1602102329
title: "buku, TLDR Pages"
description: "buku, Command-line browser-independent bookmark manager."
categories: "common"
---
> More information: <https://github.com/jarun/Buku>.

- Display all bookmarks matching "keyword" and with "privacy" tag:

```bash
buku keyword --stag privacy
```

- Add bookmark with tags "search engine" and "privacy":

```bash
buku --add https://example.com search engine, privacy
```

- Delete a bookmark:

```bash
buku --delete bookmark_id
```

- Open editor to edit a bookmark:

```bash
buku --write bookmark_id
```

- Remove "search engine" tag from a bookmark:

```bash
buku --update bookmark_id --tag - search engine
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Noemi](mailto:33022202+noemi3@users.noreply.github.com) | buku:fixe tipo (#4551) | 2020-10-07T22:25:29 | [65dcc92af08a](https://github.com/tldr-pages/tldr/commit/65dcc92af08a0d3064268df31068035a9dea7ad0)
[Raffaele Mignone](mailto:github@norangeb.it) | buku: add page (#4430) | 2020-10-05T17:22:41 | [2c7e2351e811](https://github.com/tldr-pages/tldr/commit/2c7e2351e811c3d4b638938ef59cd816d5eb0988)

