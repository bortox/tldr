---
author: ['Peter Babič']
date: 1657896456
title: "swaks, TLDR Pages"
description: "swaks, Swiss Army Knife SMTP, the all-purpose SMTP transaction tester."
categories: "linux"
---
> More information: <https://github.com/jetmore/swaks/blob/develop/doc/base.pod>.

- Deliver a standard test email to `user@example.com` on port 25 of `test-server.example.net`:

```bash
swaks --to user@example.com --server test-server.example.net
```

- Deliver a standard test email, requiring CRAM-MD5 authentication as user `me@example.com`. An "X-Test" header will be added to the email body:

```bash
swaks --to user@example.com --from me@example.com --auth CRAM-MD5 --auth-user me@example.com --header-X-Test "test_email"
```

- Test a virus scanner using EICAR in an attachment. Don't show the message DATA part:

```bash
swaks -t user@example.com --attach - --server test-server.example.com --suppress-data path/to/eicar.txt
```

- Test a spam scanner using GTUBE in the body of an email, routed via the MX records for `example.com`:

```bash
swaks --to user@example.com --body path/to/gtube_file
```

- Deliver a standard test email to `user@example.com` using the LMTP protocol via a UNIX domain socket file:

```bash
swaks --to user@example.com --socket /var/lda.sock --protocol LMTP
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Peter Babič](mailto:peter@peterbabic.dev) | swaks: add page (#7767) * swaks: add page * fix colons * Apply suggestions from code review Co-authored-by: Axel Navarro [...] | 2022-07-15T16:47:36 | [7e47ce4669f0](https://github.com/tldr-pages/tldr/commit/7e47ce4669f04c3499c7f5a55f045ec68e04d19f)

