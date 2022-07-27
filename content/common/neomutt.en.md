---
author: ['nath1as']
date: 1634425528
title: "neomutt, TLDR Pages"
description: "neomutt, NeoMutt command line email client."
categories: "common"
---
> More information: <https://neomutt.org>.

- Open the specified mailbox:

```bash
neomutt -f path/to/mailbox
```

- Start writing an email and specify a subject and a `cc` recipient:

```bash
neomutt -s "subject" -c cc@example.com recipient@example.com
```

- Send an email with files attached:

```bash
neomutt -a path/to/file1 path/to/file2 ... -- recipient@example.com
```

- Specify a file to include as the message body:

```bash
neomutt -i path/to/file recipient@example.com
```

- Specify a draft file containing the header and the body of the message, in RFC 5322 format:

```bash
neomutt -H path/to/file recipient@example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[nath1as](mailto:n@th1.as) | neomutt: add page (#6905) | 2021-10-17T01:05:28 | [b436cd44740e](https://github.com/tldr-pages/tldr/commit/b436cd44740e207da2af55fcde739cf10c0a2e3b)

