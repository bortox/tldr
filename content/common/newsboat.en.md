---
author: ['Abd El-Twab M. Fakhry', 'Hannu Hartikainen']
date: 1635184978
title: "newsboat"
description: "newsboat, An RSS/Atom feed reader for text terminals."
categories: "common"
---
> More information: <https://newsboat.org/>.

- First import feed URLs from an OPML file:

```bash
newsboat -i my-feeds.xml
```

- Alternatively, add feeds manually:

```bash
echo http://example.com/path/to/feed >> "${HOME}/.newsboat/urls"
```

- Start newsboat and refresh all feeds on startup:

```bash
newsboat -r
```

- Execute a space-separated list of commands in non-interactive mode:

```bash
newsboat -x reload print-unread ...
```

- See keyboard shortcuts (the most relevant are visible in the status line):

```bash
?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Abd El-Twab M. Fakhry](mailto:55063723+AbdeltwabMF@users.noreply.github.com) | newsboat: add -x example (#7116) | 2021-10-25T20:02:58 | [5a57e410446f](https://github.com/tldr-pages/tldr/commit/5a57e410446f12eb2df22532e0344a75eec44aea)
[Hannu Hartikainen](mailto:hannu.hartikainen@gmail.com) | newsboat: add page (#4672) | 2020-10-15T13:27:57 | [9a7b7fa841f5](https://github.com/tldr-pages/tldr/commit/9a7b7fa841f5e5ffb7e7a906065f923c13d583e4)

