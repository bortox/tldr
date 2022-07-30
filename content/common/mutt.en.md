---
author: ['bigspennyj', 'Waldir Pimenta', 'pxgamer']
date: 1559676580
title: "mutt"
description: "mutt, Command-line email client."
categories: "common"
---
> More information: <http://mutt.org>.

- Open the specified mailbox:

```bash
mutt -f mailbox
```

- Send an email and specify a subject and a cc recipient:

```bash
mutt -s subject -c cc@example.com recipient@example.com
```

- Send an email with files attached:

```bash
mutt -a file1 file2 -- recipient@example.com
```

- Specify a file to include as the message body:

```bash
mutt -i file recipient@example.com
```

- Specify a draft file containing the header and the body of the message, in RFC 5322 format:

```bash
mutt -H file recipient@example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | mutt: add link to homepage | 2019-06-04T21:29:40 | [75add6e392dc](https://github.com/tldr-pages/tldr/commit/75add6e392dc9b15dbbc3dd7eb91f782fca32e05)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | mutt: add reference to draft format as discussed in PR #1258 | 2017-05-22T17:43:10 | [08da564f800c](https://github.com/tldr-pages/tldr/commit/08da564f800c4f7617e374d309d99e79e2e6294d)
[bigspennyj](mailto:spencerdleslie@gmail.com) | mutt: add page (#1258) | 2017-05-22T08:22:55 | [04ecf81efc26](https://github.com/tldr-pages/tldr/commit/04ecf81efc26c12aa74ec49ce61a1d2d86409822)

