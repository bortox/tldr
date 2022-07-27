---
author: ['elfehr']
date: 1640846389
title: "mu, TLDR Pages"
description: "mu, Index and search emails from a local Maildir."
categories: "common"
---
> More information: <https://man.cx/mu>.

- Initialize the email database, optionally specifying the Maildir directory and email addresses:

```bash
mu init --maildir=path/to/directory --my-address=name@example.com
```

- Index new emails:

```bash
mu index
```

- Find messages using a specific keyword (in message body, subject, sender, ...):

```bash
mu find keyword
```

- Find messages to Alice with subject `jellyfish` containing the words `apples` or `oranges`:

```bash
mu find to:alice subject:jellyfish apples OR oranges
```

- Find unread messages about words starting with `soc` (the `*` only works at the end of the search term) in the Sent Items folder:

```bash
mu find 'subject:soc*' flag:unread maildir:'/Sent Items'
```

- Find messages from Sam with attached images, between 2 KiB and 2 MiB, written in 2021:

```bash
mu find 'mime:image/* size:2k..2m date:20210101..20211231 from:sam
```

- List contacts with `Bob` in either name or email address:

```bash
mu cfind Bob
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[elfehr](mailto:86655195+elfehr@users.noreply.github.com) | mu: add page (#7572) | 2021-12-30T07:39:49 | [af648ee7afd9](https://github.com/tldr-pages/tldr/commit/af648ee7afd9bd4c807845bc7e8e9cba23b24c41)

