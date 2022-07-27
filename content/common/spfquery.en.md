---
author: ['Pierre Rudloff']
date: 1588991060
title: "spfquery, TLDR Pages"
description: "spfquery, Query Sender Policy Framework records to validate e-mail senders."
categories: "common"
---
> More information: <https://www.libspf2.org/>.

- Check if an IP address is allowed to send an e-mail from the specified e-mail address:

```bash
spfquery -ip 8.8.8.8 -sender sender@example.com
```

- Turn on debugging output:

```bash
spfquery -ip 8.8.8.8 -sender sender@example.com --debug
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | spfquery: add page (#4030) | 2020-05-09T04:24:20 | [59bb357a4aa3](https://github.com/tldr-pages/tldr/commit/59bb357a4aa32e9d248e1852d1abef662828a11c)

