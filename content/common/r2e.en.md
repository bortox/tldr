---
author: ['Samuel Woon']
date: 1597014233
title: "r2e, TLDR Pages"
description: "r2e, Forwards RSS feeds to an email address."
categories: "common"
---
> Requires a configured `sendmail` or smtp setup.

> More information: <https://github.com/rss2email/rss2email>.

- Create a new feed database that sends email to an email address:

```bash
r2e new email_address
```

- Subscribe to a feed:

```bash
r2e add feed_name feed_URI
```

- Send new stories to an email address:

```bash
r2e run
```

- List all feeds:

```bash
r2e list
```

- Delete a feed at a specified index:

```bash
r2e delete index
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Samuel Woon](mailto:samuel.woon@protonmail.com) | r2e: add page (#4240) | 2020-08-10T01:03:53 | [2ead707cc3cf](https://github.com/tldr-pages/tldr/commit/2ead707cc3cffcdf8b69a53665c18359ade43552)

