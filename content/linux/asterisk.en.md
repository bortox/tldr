---
author: ['Jacob Mansfield']
date: 1602793469
title: "asterisk"
description: "asterisk, Telephone and exchange (phone) server."
categories: "linux"
---
> Used for running the server itself, and managing an already running instance.

> More information: <https://wiki.asterisk.org/wiki/display/AST/Home>.

- [R]econnect to a running server, and turn on logging 3 levels of [v]erbosity:

```bash
asterisk -r -vvv
```

- [R]econnect to a running server, run a single command, and return:

```bash
asterisk -r -x "command"
```

- Show chan_SIP clients (phones):

```bash
asterisk -r -x "sip show peers"
```

- Show active calls and channels:

```bash
asterisk -r -x "core show channels"
```

- Show voicemail mailboxes:

```bash
asterisk -r -x "voicemail show users"
```

- Terminate a channel:

```bash
asterisk -r -x "hangup request channel_ID"
```

- Reload chan_SIP configuration:

```bash
asterisk -r -x "sip reload"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jacob Mansfield](mailto:cyberjacob@gmail.com) | asterisk: add page (#4474) | 2020-10-15T22:24:29 | [d9e540a38795](https://github.com/tldr-pages/tldr/commit/d9e540a387955aca24bbaffd3a4633c8a12d4ddd)

