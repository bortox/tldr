---
author: ['Waldir Pimenta', 'Sadeed']
date: 1609242414
title: "notmuch, TLDR Pages"
description: "notmuch, Command-line based program for indexing, searching, reading, and tagging large collections of email messages."
categories: "common"
---
> More information: <https://notmuchmail.org/manpages/>.

- Configure for first use:

```bash
notmuch setup
```

- Add a tag for all messages matching a search term:

```bash
notmuch tag +custom_tag "search_term"
```

- Remove a tag for all messages matching a search term:

```bash
notmuch tag -custom_tag "search_term"
```

- Count messages matching the given search term:

```bash
notmuch count --output=messages|threads "search_term"
```

- Search for messages matching the given search term:

```bash
notmuch search --format=json|text --output=summary|threads|messages|files|tags "search_term"
```

- Limit the number of search results to X:

```bash
notmuch search --format=json|text --output=summary|threads|messages|files|tags --limit=X "search_term"
```

- Create a reply template for a set of messages:

```bash
notmuch reply --format=default|headers-only --reply-to=sender|all "search_term"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Fix syntax of "More information" links (#5050) | 2020-12-29T12:46:54 | [5430739f1dc4](https://github.com/tldr-pages/tldr/commit/5430739f1dc4d29b85b838e594550ba6c133001f)
[Sadeed](mailto:sadeeedw@gmail.com) | notmuch: add page (#4745) | 2020-10-19T20:17:44 | [43f29ee461b3](https://github.com/tldr-pages/tldr/commit/43f29ee461b36b6592fc9501d973fe96acdb285f)

